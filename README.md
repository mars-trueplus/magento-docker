### How to setup magento using this repo ###
* Clone this repo to your server
* Change Database and Magento config in 'env' file
* Get Magento file to /src folder and uncompress it
* Run command 
    * $ cd <your source folder>/src
    * $ sudo chown -R 1000:1000 ./
    * $ cd ..
    * $ docker-compose up -d
### IMPORTANT ###
Execute < your web container > with www-data user for run magento correctly
### IMPORTANT ###
* Now you can access to magento instance (default http://localhost:9200)
