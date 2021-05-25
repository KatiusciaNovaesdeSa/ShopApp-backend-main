# ShopApp-backend-main

## Project Description:
We designed an online Book store. It allows Customers to sigup, login, logout, reset their password, search items by category, add items to cart, update or delete items from cart and checkout. 
In the about us page, we can add new team members and store their images on S3 bucket. 

## Technologies Used
- Spring Boot
- Spring Data 
- Angular 
- Java Mail
- Mockito 
- Log4
- JWT Token
- S3 bucket for images storage
- Ec2 hosting for backend.


## Features

List of features ready and TODOs for future development:

- All users who register would receive a confirmation email to their email address.
- Users must login to buy books and can log out after they finish ordering.
- Users can choose books by book genres.
- The add to cart feature helps buyers keep track of their order and see the book title and quantities.
- Buyers can place orders directly and after placing the order, the cart is emptied.
- When buyers log out, the cart is still intact.
- The backend application is hosted in AWS EC2.

To-do list:

- Users can sell their own books with image uploading feature.
- Passwords should be encrypted.


## Getting Started

Backend:
git clone https://github.com/KatiusciaNovaesdeSa/ShopApp-backend-main.git


Frontend:
git clone https://github.com/KatiusciaNovaesdeSa/ShopApp-frontend-main.git

npm -i

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.


![Screen Shot 2021-05-25 at 12 21 06 PM](https://user-images.githubusercontent.com/54957332/119533698-1f99ae80-bd54-11eb-94c2-68bf4d55e125.png)

![Screen Shot 2021-05-25 at 12 21 22 PM](https://user-images.githubusercontent.com/54957332/119533725-27595300-bd54-11eb-80f4-69057a1ab79b.png)

![Screen Shot 2021-05-25 at 12 21 34 PM](https://user-images.githubusercontent.com/54957332/119533734-29bbad00-bd54-11eb-85d5-d94384c26e89.png)

![Screen Shot 2021-05-25 at 12 21 53 PM](https://user-images.githubusercontent.com/54957332/119533777-33ddab80-bd54-11eb-8a75-01b9c66d7557.png)

![Screen Shot 2021-05-25 at 12 21 42 PM](https://user-images.githubusercontent.com/54957332/119533757-2fb18e00-bd54-11eb-8101-3361c6e4ab76.png)

![Screen Shot 2021-05-25 at 12 22 00 PM](https://user-images.githubusercontent.com/54957332/119533793-38a25f80-bd54-11eb-8508-a137c90dced6.png)

![Screen Shot 2021-05-25 at 12 22 10 PM](https://user-images.githubusercontent.com/54957332/119533828-422bc780-bd54-11eb-9cc9-60efc22e3c0c.png)

![Screen Shot 2021-05-25 at 12 22 52 PM](https://user-images.githubusercontent.com/54957332/119533848-46f07b80-bd54-11eb-9cb0-d3de31cbbd29.png)

![Screen Shot 2021-05-25 at 12 23 00 PM](https://user-images.githubusercontent.com/54957332/119533874-4bb52f80-bd54-11eb-8cf9-bac5c2857b5d.png)



## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests


Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.


