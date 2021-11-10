# MIS 362-03 Management Information Systems

## 0. Computer and Work Setup 101

[0. Setup Your Computer](https://zwentt.github.io/wsu-mis-362/0.%20Setup%20Your%20Computer){:target="_blank"}

## 1. Virtual Machine

[1.1 Download VirtualBox and Pure OS](https://zwentt.github.io/wsu-mis-362/1.1%20Download%20VirtualBox%20and%20Pure%20OS){:target="_blank"}

[1.2 Install and Setup VirtualBox in Windows](https://zwentt.github.io/wsu-mis-362/1.2%20Install%20and%20Setup%20Virtual%20Machine){:target="_blank"}

[1.2.1 Install and Setup VirtualBox in macOS](https://github.com/zwentt/wsu-mis-362/blob/main/1.2.1%20Install%20and%20Setup%20VirtualBox%20Software%20on%20a%20macOS.pdf){:target="_blank"}

[1.3 Configure VirtualBox to Create the Your First Virtual Machine](https://zwentt.github.io/wsu-mis-362/1.3%20Configure%20VirtualBox%20to%20Create%20the%20First%20Virtual%20Machine){:target="_blank"}

[1.4 Install Pure OS on the Virtual Machine](https://zwentt.github.io/wsu-mis-362/1.4%20Install%20PureOS%20on%20the%20Virtual%20Machine){:target="_blank"}

[1.5 Assignments](https://zwentt.github.io/wsu-mis-362/1.5%20Assignments){:target="_blank"}

`sha256sum`, `wget`, `sudo`,  `apt`, 

## 2. Raspberry Pi Initial Setup 

[2.0 Get Raspberry Pi 3 B+ Ready](https://zwentt.github.io/wsu-mis-362/2.0%20Get%20Raspberry%20Pi%203%20B%2B%20Ready){:target="_blank"}

[2.1 Install Raspberry Pi OS](https://zwentt.github.io/wsu-mis-362/2.1%20Install%20Raspberry%20Pi%20OS%20){:target="_blank"}

[2.2 Connect to an External Display](https://zwentt.github.io/wsu-mis-362/2.2%20Connect%20to%20an%20External%20Display%20%26%20VNC){:target="_blank"}

`wget`

[2.3 Raspberry Pi Initial Configuration](https://zwentt.github.io/wsu-mis-362/2.3%20Raspberry%20Pi%20Initial%20Configuration){:target="_blank"}

`sudo poweroff`

[2.4 Obtain the IP Address of Your R-Pi](https://zwentt.github.io/wsu-mis-362/2.4%20Obtain%20the%20IP%20Address%20of%20Your%20Pi){:target="_blank"}

`hostname`

[2.5 Configure VNC for Remote Connection](https://zwentt.github.io/wsu-mis-362/2.5%20Configure%20VNC%20for%20Remote%20Connection){:target="_blank"}

[2.6 Connect to Pi Using SSH](https://zwentt.github.io/wsu-mis-362/2.6%20Connect%20to%20Pi%20using%20SSH){:target="_blank"}

`ssh`, `cmatrix`

## 3. Database Exercises using MariaDB 

[3.0 Setup MariaDB in Raspberry Pi](https://zwentt.github.io/wsu-mis-362/3.0%20Setup%20MariaDB){:target="_blank"}

`update`, `dist-upgrade`, `mariadb-server` package, 

`SHOW DATABASES`, 

[3.1 Manage User Access](https://zwentt.github.io/wsu-mis-362/3.1%20Manage%20User%20Access){:target="_blank"}

`mysql_secure_installation`, MariaDB login, `CREATE USER`, `GRANT ALL PRIVILEGES`, 

[3.2 SQL Fundamentals - Creating Database and Tables](https://zwentt.github.io/wsu-mis-362/3.2%20SQL%20Fundamentals%20Creating%20Database%20and%20Tables){:target="_blank"}

`CREATE DATABASE`, `SHOW DATABASE`, `USE`, `CREATE TABLE`, `DESC table`, `SHOW TABLES`, `SELECT`, `FROM`, `WHERE`, `INSERT INTO`, `UPDATE`, 

[3.2.1 SQL Fundamentals - Examples of Errors](https://zwentt.github.io/wsu-mis-362/3.2.1%20SQL%20Fundamentals%20-%20Examples%20of%20Errors%20){:target="_blank"}

`SHOW WARNINGS`, 

[3.3 Example Database - Sakila](https://zwentt.github.io/wsu-mis-362/3.3%20Example%20Database%20-%20Sakila){:target="_blank"} 

`cd`, `ls`, `unzip`, import `sakila` using `<` , `ER-Diagram`, 

[3.4 More SQL Exercises](https://zwentt.github.io/wsu-mis-362/3.4%20More%20SQL%20Exercises){:target="_blank"}

`ORDER BY`, `COUNT(*)`, `DISTINCT`, `AND`, `OR`, `LIKE`, `JOIN`

## 4. A Simple Example of Business Intelligence & Analytics

[4.0 A Simple Example - Introductory Comments](https://zwentt.github.io/wsu-mis-362/4.0%20A%20Simple%20Example%20for%20Analytics){:target="_blank"}

[4.1 Exporting Data for Analytics - Part 1/2](https://zwentt.github.io/wsu-mis-362/4.1%20Exporting%20Data%20for%20Analytics){:target="_blank"}

`bank` database, `LIMIT`, `INTO OUTFILE`, `FIELDS TERMINATED BY`, `LINES TERMINATED BY`, `/tmp` directory, `apache` package, `mv`, `FiliZilla`, `Notepad+`, `Sublime Text`

[4.1.1 Data in its Naked Form](https://zwentt.github.io/wsu-mis-362/4.1.1%20Data%20in%20its%20Naked%20Form){:target="_blank"}

`tab separated`, `comma separated`, `delimiters`, `Text to Columns`, 

[4.2 Exporting Data for Analytics - Part 2/2](https://zwentt.github.io/wsu-mis-362/4.2%20Exporting%20Data%20for%20Analytics%20-%20Part%202){:target="_blank"}

`UNION ALL`, `INTO OUTFILE`, export a table with header

[4.2.1 Structured Manipulation of Text Data](https://zwentt.github.io/wsu-mis-362/4.2.1%20Structured%20Handling%20of%20Text%20Data){:target="_blank"}

text vector to Excel column, Excel column to text vector, import data from web to Excel, 

4.3 Descriptive and Predictive Analytics Demo{:target="_blank"}

## 5. Apache Web Server

[5.0 Setup Raspberry Pi as a Web Server](https://zwentt.github.io/wsu-mis-362/5.0%20Setup%20Raspberry%20Pi%20as%20a%20Web%20Server){:target="_blank"}

[5.1 Setup Apache Server](https://zwentt.github.io/wsu-mis-362/5.1%20Setup%20Apache%20Server){:target="_blank"}

`apache` server installation, 

[5.2 Understand Apache Root Directory](https://zwentt.github.io/wsu-mis-362/5.2%20Understand%20Apache%20Root%20Directory){:target="_blank"}

`/var/www/html/`, `pwd`, 

[5.3 Setting Permission of the Root Directory](https://zwentt.github.io/wsu-mis-362/5.3%20Setting%20Permission%20of%20the%20Root%20Directory){:target="_blank"}

`ls -la`, `chown`, 

[5.4 Host an Example Web Page](https://zwentt.github.io/wsu-mis-362/5.4%20Host%20an%20Example%20Web%20Page){:target="_blank"}

Creating a web page file from Word, 

[5.5 Install MariaDB Web Interface](https://zwentt.github.io/wsu-mis-362/5.5%20Install%20MariaDB%20Web%20Interface){:target="_blank"}

`phpmyadmin`, `nano`, 

## 6. Network Application 

[6.0 Network Applications](https://zwentt.github.io/wsu-mis-362/6.0%20Network%20Applications){:target="_blank"}

[6.1 Basic Linux Terminal Commands](https://zwentt.github.io/wsu-mis-362/6.1%20Basic%20Linux%20Terminal%20Command){:target="_blank"}

`ping`, `traceroute`

[6.2 Use Wireshark to Listen to the Network](https://zwentt.github.io/wsu-mis-362/6.2%20Use%20Wireshark%20to%20Listen%20to%20the%20Network){:target="_blank"}

`wireshark`
