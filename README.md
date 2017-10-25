# PRIMAVERA IMS v1

### A savvy yet straightforward inventory management system

Primavera is an inventory management system based on **Siamon Hasan**'s [OSWA-INV](https://oswapp.com) which is powered by [PHP](http://php.net/),[MySQL](https://www.mysql.com/) and [Bootstrap](http://getbootstrap.com/). 

Primavera functions like any inventory management systems do: tracking factors such as price, quantity, flow of products from one place to another and many more. However aside from its flexibility, Primavera also ensures a good visual experience optimized with the user's visual health in mind without compromising functionality whatsoever. Made with a pastel theming and adjusted font sizes for visual comfort, Primavera will assure you a seamless and comfortable workflow.

### Installation
****

1. Fire up Git and download
   > `git clone https://github.com/znraznra/primavera-ims`
2. Import primavera.sql using MySQL.
3. Modify **includes/config.php** and adjust the values to match yours *(host, database, username, password, etc)*
4. Change all folder permissions inside uploads folder.
   > Add them to group call `www` or `777`, whichever's applicable.
5. Finally, log in using these master credentials that you can change or customize later on.

   Admin                | Custom *(in case of users with limited privileges)* | Default *(basic permissions)*
   ---------------------| --------------------------------------------------- | -----------------------------
   **Username** : admin | **Username** : custom                               | **Username** : default
   **Password** : 12345 | **Password** : 12345                                | **Password** : 12345

6. It's all set now. Have fun!  
