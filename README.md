# XAMPP - MySQL - FIX

## Block Port Fix

1. Rename folder **mysql/data** to **mysql/data_old**
2. Make a copy of **mysql/backup** folder and name it as **mysql/data**
3. Copy all your database folders from **mysql/data_old** into **mysql/data** (except **mysql**, **performance_schema**, and **phpmyadmin** folders)
4. Copy **mysql/data_old/ibdata1** file into **mysql/data** folder
5. **Start** MySQL from XAMPP control panel

