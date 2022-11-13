<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://tutsforweb.com/wp-content/uploads/2018/06/cron-750x430.png" width="400"></a></p>


## What is task scheduling in Laravel?

The scheduler allows you to fluently and expressively define your command schedule within your Laravel application itself. When using the scheduler, only a single cron entry is needed on your server. Your task schedule is defined in the app/Console/Kernel.php file's schedule method.

https://laravel.com/docs/9.x/scheduling

## Why we have to use cron job?

Many times we need to send notifications or send email automatically to users for update property or products. So at that time you can define some basic logic for each days, hours etc can run and send email notification.

## Process

- php artisan make:command DemoCron --command=demo:cron
- php artisan schedule:run
- we need to define our commands on Kernel.php file with time when you want to run your command like as bellow functions:


<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://user-images.githubusercontent.com/80118217/201533854-704b1eda-156a-4e15-a382-857666d4aadf.JPG" width="600"></a></p>


## Output

<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://user-images.githubusercontent.com/80118217/201479037-89e9c77d-bb67-458e-a990-1a349aef3899.JPG" width="400"></a></p>



<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://user-images.githubusercontent.com/80118217/201479089-acaee851-585a-41e3-b889-fea768cd4995.JPG" width="400"></a></p>


<p align="center"><span style="color: red;">&hearts;</span> Thank You <span style="color: red;">&hearts;</span></p>
