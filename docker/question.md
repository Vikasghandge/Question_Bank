1) What is a Multi-Stage Build and why should you use it?
   ans:- It allows you to use one "heavy" image to build/compile your code and then copy the final binary into a    "           light" production image (like Alpine). This keeps image sizes small and secure.


 2) What is a "Dangling Image" and how do you clean it up?
     ans:- dangle images are basically are unused images like this previous version of any when we make changes any
           image and then rebuild it with same name and tag it will create two old image will become the dangle image
           that image will not have tag and name.  
