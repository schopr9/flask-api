python migrate.py db init
python migrate.py db migrate
python migrate.py db update
python run.py

POST /group/new

{
    "data": 
      {
        "attributes": {
          "name": "postbeyond1"
        },
        "type": "groups"
      }
      
}

POST /user/new
{
    "data": 
      {
        "attributes": {
          "email": "mohit.chopra@gmail.com", 
          "username": "mohit007"
        },
        "type": "users"
      }
}

POST /user/:id/groups

{
<<<<<<< HEAD
    groups : [1,3,5]
}
=======
    groups : [1,3,5]
}
>>>>>>> fc3e6f53d4fab3809092a6cf35b81099dfd51d73
