# pbAPI
pbAPI is an elaborate php file that can be accessed easily through your php web app to serve complex functions without doing any work.<br>
# An example API request asking for the current date
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
| date | returns the current date (UTC)|
| ip| returns user ip |
| day| returns current day of week (UTC) |
| time| returns current time of day (UTC) |
