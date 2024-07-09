# Online_Food_Ordering_System
This project is a food ordering system, implimented using C language. The code has been sub-divided into separate sub-programs according to the functioanlities used in the program. This makes the problem easy and simple to understand & debug. This approach of programming is called Modular Programming.
It has the following functionalities:
* Signup & Login
* Validating user account
* Search by food
* Search by hotel name
* Cart and order confirmation

  # Aprroach

  Sign-up

User has to sign then login before ordering food.

The following inputs have to be submitted by user:

* Name
* Email id
* Age
* Password
* Confirm the password
* Mobile number

Validation

For validating the user account the following criteria must match with the user details. Otherwise user account will be invalid. If all the details are correct user account will be created.

* Name  : User name must contains alphabets, user can input first name & last name.
* Age: Age must be greater than and not equal to 0.
* Email:
      First character must be an alphhabet(no numbers or symbols).
      There must be a '@' in the id prior to the '.'
      There should be a domain name after '@' & before '.'
      There should be a dot at the end of id.
* Password:
      Length of password must be between 8 to 12 characters.
      There must be at least one uppercase, lowercase, number and special character.
      Both password and confirm password should be the same.

  Login

  Email & password are checked & must match with the user details.
  
