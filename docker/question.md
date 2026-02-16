1) What is a Multi-Stage Build and why should you use it?
```
   ans:- It allows you to use one "heavy" image to build/compile your code and then copy
the final binary into a    "
 light" production image (like Alpine). This keeps image sizes small and secure.
```


 2) What is a "Dangling Image" and how do you clean it up?

    ```
     ans:- dangle images are basically are unused images like this previous version of any when we make changes any
           image and then rebuild it with same name and tag it will create two old image will become the dangle image
           that image will not have tag and name.  
```

3) "You have a docker-compose.yml file with a Web App and a Database. You use the depends_on property to make sure the Database starts before the Web App.



```
ans:-  depends on will only tell mysql is started or not but will not tell ki container is reday or not to accept
connections  we need to add some health checks and condition is database is ready or not
```
