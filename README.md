# MusicLibrary

### Description

MusicLibrary offers a complete solution for managing music collections, catering to enthusiasts who seek a user-friendly platform for organizing, storing, editing, and discovering their favorite albums. Its intuitive interface and robust features enable users to effortlessly curate their music while ensuring security through authentication and authorization protocols.
---
### Installation and set up

To install all dependencies listed in the `package.json` file of your project. Run the following command:

```
npm install
```

To start the project, execute `npm start`. It should run the project on http://localhost:3000/

```
npm start

```
clone  the repostitory

```
git clone "link of your repository"

---

navigate to the project directory

````
cd MusicLibrary

---
### REST Api

* GET /data/albums?sortBy=_createdOn%20desc
* GET /data/albums/:id
* POST /data/albums
	* body { singer: string, album: string, imageUrl: string, release: number, label: string, sales: string }
* PUT /data/albums/:id
* DELETE /data/albums/:id
* POST /users/login
	* body { email: string, password: string }
* POST /users/register
* GET /users/logout
* POST /data/likes
	* body { albumId: string }
* GET /data/likes?where=albumId%3d%22:albumId%22%20&distinct=_ownerId&count

---

### Pages and Permission 

* All Users
  * Home
  * Dashboard
  * Login
  * Register
  * Details
 
* Authenticate Users
  * Create
  * Edit
  * Details
  * Home
  * Dashboard

  ---
  Technologies

  ```
  HTML

  ```

  CSS

  ```

  JavaScript

  ```

  Lit HTMl

  ```

  Lite server

  
  
