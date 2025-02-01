
# XAMPP Setup Guide

1. **Install XAMPP** from [here](https://www.apachefriends.org/index.html).
2. **Start Apache and MySQL** using the XAMPP control panel.
3. **Access the Database** by navigating to `http://localhost/phpmyadmin`.
4. If you face issues with the database, check the following:
   - Ensure the MySQL service is running.
   - Check for any errors in the XAMPP control panel.

For more detailed troubleshooting, watch this video:  
[How to fix XAMPP database issues](https://www.youtube.com/watch?v=84IOtc05TuA)


# How to create a folder apache in linux
- just follow the code just change the adornado:adornado based on your linux computer name
```php
sudo chown -R adornado:adornado /var/www/html/E-commerce
```
- then add this for security fatures in the website

```php
sudo chmod -R 755 /var/www/html/E-commerce
```
- Now you can finally  enjoy coding in your e-commerce project

# Reinstalling XAMPP (if needed)

If you need to reinstall XAMPP or its components, you can follow the steps below to install it as a single package. This guide assumes you're using a Linux system.

---

### Steps to Reinstall XAMPP

#### 1. **Download XAMPP:**
   - Visit the official [XAMPP website](https://www.apachefriends.org/index.html) and download the Linux version of XAMPP.
   - Make sure to download the appropriate version of the installer (e.g., `xampp-linux-x64-<version>.run`).

#### 2. **Make the Installer Executable:**
   After downloading the installer, open a terminal and navigate to the folder where the installer is saved. Then run:

```php
   chmod +x xampp-linux-x64-8.2.12-0-installer.run
```

This command gives the installer the necessary execute permissions.

3. Run the Installer:
Run the installer with root privileges using the following command:

```php
sudo ./xampp-linux-x64-8.2.12-0-installer.run
```
Follow the on-screen instructions to complete the installation.

4. Start XAMPP:
Once installed, you can start XAMPP by running:

```php
sudo /opt/lampp/lampp start
```
This command starts Apache, MySQL/MariaDB, and other components of XAMPP.

5. Access XAMPP:
Open your web browser and go to:
http://localhost


You should be able to access the XAMPP dashboard and begin using it.


