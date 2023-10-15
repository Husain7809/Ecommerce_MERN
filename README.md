<!-- project installation process -->

 1. clone this project => 
# https://github.com/Husain7809/Ecommerce_MERN.git'

2. npm i --force => for install backend packages

3. cd frontend => change folder

4. npm i --force => for install frontend packages

5. create a config.env file for backend =>  set config for backend
    ./backend/config => config.env

    Below code set for backend sever

   # config.env setup for backend
    ```
    PORT= 4000 
    DB_URI = mongodb://127.0.0.1:27017/Ecommerce

    STRIPE_API_KEY= 
    STRIPE_SECRET_KEY= 

    JWT_SECRET= asdfgjhgfdsdfghjgfdsgjuuikiki
    JWT_EXPIRE= 7days

    COOKIE_EXPIRE= 7

    SMPT_SERVICE = ssl
    SMPT_MAIL= 
    SMPT_PASSWORD= 
    SMPT_HOST= smtp.gmail.com
    SMPT_PORT= 465

    CLOUDINARY_NAME=
    CLOUDINARY_API_KEY= 
    CLOUDINARY_API_SECRET= 
    ```

6. Backend Run => npm run dev

7. frontend Run => npm run start

8. http://localhost:3000/