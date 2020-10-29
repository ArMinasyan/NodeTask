# Node.js Task 

- Create application with Node and Express.js.
- The Application should request and take information about `/users`, their `/albumns` and `/photos` from JsonPlaceholder[^1] and place in your local Database.
- We prefer to use Postgres as a DB, but you free to use any relational or non-relational DB like MongoDB.
- On the other hand you will provide the `/users` REST enpoints for your backend, which will provide the users list, included albumns and photos.
- On the other hand you will provide the REST endpoints for `/users`, which will accept 4 http methods: `GET`, `POST`, `PUT`, `DELETE`
  - `GET` - return the users list with included albumns and photos from your local DB
  - `POST` - create the user without albumn and photo in your local DB
  - `PUT` - update the user information depends on user id
  - `DELETE` - remove the user from your local DB.
- Writing the code with Typescript can be a big plus.  
  
## Expectations
Document your coding process with Git and publish your result to the repository you got along with
this tasks. 
We will then clone your code and run it locally on our machines.
The result in the repository should be a git history of your development process (a single commit with
the complete application is not acceptable. We want to see multiple commits showing your
progress), a README document on how to install and start your application, and a package.json
with scripts to build and serve your application.
Simple is better than complicated. Consider your application a proof-of-concept, quicker development using tools to achieve the result is better
than hand crafting every line but taking 5x as long. You can use whatever resources or libraries
open-source in addition (but not as a replacement) of the libraries previously mentioned. If you
use a cli that writes 98% of your code, fine! 
If you have any questions do not hesitate to contact us.
[^1]: https://jsonplaceholder.typicode.com/
