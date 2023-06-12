
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/logo.png" width="70%">
</p>


This project is built on top of [Laravel (v6) skeleton](https://github.com/rdehnhardt/skeleton).

## How to register

This application has a disabled registration page. However, I plan to have a `api/signup` page which after email verification is limited.  A completed bio / profile is needed for mod approval to be able to do certain things.


### TODO
- [] Reg page with mod approval 

ut accounts are only activated if email verified and has been approved by another member. 

## Route system

The routing folder for this application has been changed to the application Http folder.
 
Directory: `app/Http/Routes`

## How to install

First make storage folder writable. 

```
cp .env.example .env
```

```
composer install
```

```
php artisan key:generate
```

```
php artisan migrate --seed
```

```
php artisan storage:link
```


# Screenshots

#### Front
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/screen/front.png">
</p>

#### Login
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/screen/login.png">
</p>

#### Dashboard
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/screen/dashboard.png">
</p>

#### User List
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/screen/users-list.png">
</p>

#### User Edit
<p align="center">
  <img src="https://raw.githubusercontent.com/rdehnhardt/skeleton/master/public/img/screen/user-edit.png">
</p>
