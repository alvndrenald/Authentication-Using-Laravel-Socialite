# Authentication-Using-Laravel-Socialite
Installation Guide

create project laravel dengan composer create-project laravel/laravel auth-> nama project

create database di phpmyadmin dan ganti DB_DATABASE sesuai dengan nama database yang sudah dibuat

composer require laravel/ui

php artisan ui bootstrap --auth

npm install $& npm run dev

add button "Sign in using Google" and "Sign in using Github"

setting config/services.php

setting env

create route di routes/web.php

add function untuk redirect and callback di controller

add provider_id dan avatar di tabel users

php artisan serve
