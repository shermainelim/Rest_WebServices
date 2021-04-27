# RESTful Web Services

Social Media Application

User -> Posts

- Retrieve all Users - GET /users
- Create a User      - POST /users
- Retrieve one User  - GET /users{id} -> /users/1
- Delete a User      - DELETE /users/{id} -> /users/1

- Retrieve all posts for a User - GET/users/{id}/posts
- Create a posts for a User     - POST /users/{id}/posts
- Retrieve details of a post 	- GET /users/{id}/posts/{post_id}  

//GET
//URI - /hello-world
//method - "Hello World"

//@RequestMapping(method=RequestMethod.GET,path="/hello-world")

@GetMapping(path="/hello-world")

# Path Variable
![image](https://user-images.githubusercontent.com/65886071/116241744-d4619f80-a797-11eb-8851-75a2df2cab0d.png)

![image](https://user-images.githubusercontent.com/65886071/116241580-9ebcb680-a797-11eb-8ef9-3fbc1d6a9592.png)

![image](https://user-images.githubusercontent.com/65886071/116241844-ecd1ba00-a797-11eb-9d14-f011fef777d1.png)
