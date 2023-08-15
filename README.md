# Flower-Management-System
A flower management system is a user-friendly online platform that caters to the needs of florists and flower shops. It provides essential features like flower catalog display, order placement, and customer engagement. Through an intuitive interface, users can explore a range of flowers, select arrangements, and conveniently place orders..



Sure, here are the simple steps to install XAMPP and load SQL:
**Installing XAMPP:**

1. **Download XAMPP:** Go to the official XAMPP website (https://www.apachefriends.org/) and download the XAMPP installer for your operating system (Windows, macOS, or Linux).

2. **Run Installer:** Double-click the downloaded installer file and follow the on-screen instructions to install XAMPP. Choose the components you want to install (Apache, MySQL, PHP, etc.).

3. **Select Installation Location:** Choose a directory where you want to install XAMPP. The default location is usually fine.

4. **Start Services:** After installation, launch XAMPP Control Panel and start the Apache and MySQL services.

**Loading SQL Database:**

1. **Access phpMyAdmin:** Open your web browser and navigate to http://localhost/phpmyadmin/ (if you've installed XAMPP locally).

2. **Login:** Log in to phpMyAdmin using the username "root" and no password (if you didn't set a password during XAMPP installation).

3. **Import SQL File:** Once logged in, click on the "Import" tab in phpMyAdmin. Choose the SQL file(shop_db) to import.

4. **Choose File:** Click the "Browse" button and select the SQL file from your computer.

5. **Import Settings:** If needed, adjust import settings like character set and format. Usually, the default settings work fine.

6. **Import:** Click the "Go" button to start importing the SQL file. The database and its content will be imported into your local MySQL server.

7. **Confirmation:** Once the import is complete, you'll receive a confirmation message.

Remember to replace "localhost" with the appropriate server address if you're using a remote server.

<h3>Note:</h3>
The flower management system uses the same login page for both users and administrators, Users and administrators can access their respective accounts through a single point of entry

<h3>For Admin Panel</h3>
Email: admin@gmail.com </br>
password: admin </br>
username: admin </br>
</br>

If the above login credentials for admin are not working then:</br>
1. go to the database(i.e shop_db) </br>
2. choose users from the table </br>
3. click on edit for the specific user in order to change the user_type </br>
4. change the user_type from user to admin </br>
5. click on go
