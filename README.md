#HTTP Parser
##Description
This HTTP Parser will dissect HTTP requests and returns information based on what was within the HTTP request. 

##How to Use

1. Run `bundle install` from the command line while in the main directory.
2. Run `ruby bin/run.rb` from the command line while in the main directory.
3. Once at the program's main menu, type `q` to quit, type `h` for help, or input a valid HTTP request.

- For example, if you input `GET http://localhost:3000/users HTTP/1.1`, you will get a list of every user's first name, last name, and age.
-  If you want to do a more specific search, you can get back one user. For example, if you input `GET http://localhost:3000/users/1 HTTP/1.1`, you will get back only the user whose ID is 1.
-  If you put in a user id number that doesn't exist, you will get back response code 404, which means that the user couldn't be found.