# Scrapy14
Scraping News Stories - Multiple Sources

#### Example for YouTube (https://www.youtube.com/c/DrPiCode)

#### Objective : Multiple spiders using ONE items.py with MySQL database for consistent data 

## Add new database to MySQL

    sudo mysql -u root -p -h localhost

    DROP DATABASE IF EXISTS newz;
    CREATE DATABASE newz;

    GRANT ALL PRIVILEGES ON newz.* TO 'pi'@'localhost';

    FLUSH PRIVILEGES;

### Check all potential news sites in Scrapy shell first

#### Use scrapy shell's fetch (url, headers={})

*Also you can check with scrapy shell and curl*

![Curl from Browser](https://user-images.githubusercontent.com/62441426/103042322-276ce100-4571-11eb-9c21-b30c26f08598.png)

![Curl Scrapy](https://user-images.githubusercontent.com/62441426/103042367-43708280-4571-11eb-9d4e-783bab6a7eb7.png)

### Plan the columns / fields for "items" to scrape







