## Project



<br>

## Project Name
>> GET-FIT

   

<br>

# DEPLOYED LINK
 - [Frontend](https://delightful-manatee-b9b034.netlify.app/frontend/)
 - [Backend](https://outstanding-gold-ladybug.cyclic.app/)

<hr>

 


 # REQUIREMENTS 
  - User can login and sign up 
  - User can visit severals sections
  - User can able to get all the information
  - User can book trainers
  - User can book other services
  - User can book the appointment slot 
  - User can choose time according to their needs for slot booking
  - Feedback


  ## TECH STACKS
   # Frontend
    >HTML
    >CSS
    >JAVASCRIPT
    >BOOTSTRAP

   # Backend
    >NODEJS
    >EXPRESSJS
    >MONGOOSE
    >NODEMAILER
    >JSONWEBTOKEN
    >BCRYPT
    >CORS
    
   # Database
    >MONGODB

   ## Register

    - "https://outstanding-gold-ladybug.cyclic.app//user/signup"

    * User 
    - Name 
    - Email
    - Password

   ## Login

     - "https://outstanding-gold-ladybug.cyclic.app//user/login"

     - Email
     - Password
     
     
     
     


    
## Home Page
 - Navbar -> Home | About | Features | Pricing | Trainers | Register Now
 - Header
 - Footer





  ## Schema
    ## User
    - name  : String
    - email : String
    - password : String
    ## Trainer
    - name : String
    - age : String
    - gender : String
    - image : String
    - price : Number
    - specialization: Array of String
    ## Booking
    - userId : String
    - trainerId : String
    - userEmail : String
    - bookingDate : String
    - bookingSlot : String
 
 ## Booking end points
 - Adding new booking
  - https://outstanding-gold-ladybug.cyclic.app/booking/create

    - trainerId
    - bookingDate
    - bookingSlot

 - Cancelling the booking
  - https://outstanding-gold-ladybug.cyclic.app/booking/remove/id

 - Get all booking
  - https://outstanding-gold-ladybug.cyclic.app/booking

 - Get the booking of paticular user
  -https://outstanding-gold-ladybug.cyclic.app/booking/userId

 ## Trainer end points
  - Get all trainer
   - https://outstanding-gold-ladybug.cyclic.app/trainer
  
  - Add new trainer
   - https://outstanding-gold-ladybug.cyclic.app/trainer/add

      - name 
      - age 
      - gender 
      - image 
      - price 
      - specialization
      
  - Get a paticular trainer by trainerId
    -https://outstanding-gold-ladybug.cyclic.app/trainer/id

    

    




    


