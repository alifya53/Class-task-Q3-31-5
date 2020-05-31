#IOT Class TASK

Create a server which get a number in parameter and return the number + 50

first add rocket in toml file

[dependencies]
rocket = "0.4.4"

then import in main.rs file

#![feature(proc_macro_hygiene, decl_macro)]
#[macro_use] extern crate rocket;
use rocket::request::Form;
use rocket::response::NamedFile;

Now creat a folder in main Name Static

now create html file name index.html and 
create a form in html with one input feild and submit button and form action = "/" and method ="post"

Now , Run the code ! Happy Coding...!!!
