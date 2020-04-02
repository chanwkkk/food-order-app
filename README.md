# food-order-app

## Introduction

This is a project that allows people to order food online.  It is a combination of a react-based frontend and a rails API backend.

## Installation

### Set up the backend

Put this in your terminal:

```ruby
git@github.com:chanwkkk/food-order-app.git
```

And then go inside the folder by typing this in your terminal:

```
cd food-order-app
```

To view the page correctly, you have to run the application server first. So go to the backend folder: 

```
cd ghibli-movies-backend
```

And then install all missing gems by input:
```
bundle install
```

And since the frontend code is conducted on the base of port 3001, so MAKE SURE you run the program at port 3001: 

```
rails s -p 3001
```
After that, you should be able to see the following sentences:

```
=> Booting Puma
=> Rails 6.0.2.1 application starting in development 
=> Run `rails server --help` for more startup options
Puma starting in single mode...
* Version 4.3.3 (ruby 2.6.1-p33), codename: Mysterious Traveller
* Min threads: 5, max threads: 5
* Environment: development
* Listening on tcp://127.0.0.1:3001
* Listening on tcp://[::1]:3001
Use Ctrl-C to stop
```
That means the server is working now. 

### Set up the frontend

After you set up the backend, simply going back to your main folder by running: 

```
cd ..
```

After you see you come back to `food-order-app`, run this to go to the frontend folder: 

```
cd frontend
```

Then run `npm install` to install all packages and `npm start` to start to see the website.

You can sign up, log in, go to the `Homepage` to order food and go to `My orders` page to check out your order histories and submit your current order. 




