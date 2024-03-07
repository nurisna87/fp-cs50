# Overview
‘UMKM Promotion Website’ is a web-based application developed with HTML, CSS, JavaScript and SQLite.
This application is free for use and is available in https://nurisna87.github.io/fp-cs50/
Link to the video: https://youtu.be/OEcEMg8AqUk

# Database Schema
The database is designed for storing  user information after the user registering on our website, they can make an account. The function of the account is that the user can submit their UMKM. The admin can select the user submitting.

register table: to store each ingredient's category. It's related to the register table, referenced by the id.
    CREATE TABLE "regiter" (
    	"firstname"	varchar NOT NULL,
    	"lastname"	varchar NOT NULL,
    	"email"	varchar NOT NULL,
    	"password"	varchar NOT NULL,
    	"comfirmpassword"	varchar NOT NULL,
     )

   We put coding suggestion table on contact html.
      CREATE TABLE "suggest" (
      	"yourname"	varchar NOT NULL,
      	"youremail"	varchar NOT NULL,
      	"yourphonenumber"	varchar NOT NULL,
      	"yournantionality"	varchar NOT NULL,
      	"yoursubject"varchar NOT NULL,
      	"massage"varchar NOT NULL,
      )


# Structure
    Website of Mediartha.com
        Home
        Service
        Portofolio
            Portofolio Video
                Video
            Portofolio Foto
                Img
            Portofolio Drone
                Video
        Staff
        Contact
            Comment
            Register
            Login
        Dynamic Website
        Blog
        


