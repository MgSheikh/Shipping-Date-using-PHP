# Calculate shipping date based on nonworking days
Imagine there is a webshop which sells some products. We need the code that calculates the
expected shipping date when a user submits an order. The shop owner has decided NOT to ship
on certain days of the week ($holidays variable in config.php). There is a cut off time for placing
an order that will be shipped on the same day, for example, orders placed before 11 in the
morning will be shipped on the same day, else it will only be shipped the next day/next shipping
allowed day ($cutOffTime in config.php). Shipping means handing over the package to the
courier company.

The main code with logic should be added to getShippingDate in functions.php and it should
return the date (Y-m-d format) in which the product will be shipped.


# Installation

Its need PHP environment.

To change the number of holidays inside /functions.php 
```PHP
 $allHolidays = array('10-08-2022','11-08-2022', '12-08-2022','13-08-2022');
 ```
To change the Cut off time
```PHP
$cutOffTime = "11:00"; 
```
# View

![image](https://user-images.githubusercontent.com/110724391/183831068-7d22b2b9-a02a-4c41-b765-e202ee41a202.png)

# Video Explained
![GET ECOM SHIPPING DATE](https://user-images.githubusercontent.com/110724391/184474669-269c1870-3296-403a-9a81-a62f66193c5a.png)
