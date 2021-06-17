<p align="center">
<img src="https://github.com/AyatANSSAIEN/Car-Location/blob/master/public/img/logoW.png" width="100">
<img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400">
</p>


# Car Rent

Car rent made with laravel 8, jetstream, tailWindCSS And liveWire 

## Usage 

to use this application you must :

- create data base **location** or you can choose another name and change it in the **.env** file.

- to migrate database and seeders , open a new terminal then run this commands

```bash
php artisan migrate 
composer dump-autoload 
php artisan db:seed
```
- to run the schedule tasks that works every day, open a new terminal then run this command

```bash
php artisan schedule:work
```
