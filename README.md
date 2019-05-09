# pbAPI
pbAPI is a complex php file that can be accessed easily through your php web app to serve complex functions without doin  any work
A example API request asking for the current date
```php
<?php
$date = file_get_contents("https://www.persistentbits.com/pbAPI?q=date");
echo $date;
?>
```
#  Or for even more advanced requests
Here getting a user's ip
```php
<?php
$ip = file_get_contents("https://www.persistentbits.com/pbAPI?q=ip");
echo $ip;
?>
```

| q=| Description |
| --- | --- |
| date | gives the current date |
| ip| return user ip |
| day| returns current day of week |
| time| returns current time of day
