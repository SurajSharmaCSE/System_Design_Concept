Object -> toString, equals, hashcode

Notes
1. Base class of all classes in Java is Object
2. Why does ArrayList, LinkedList, HashMap etc. print their content in syso and our class doesnot do it?
    -> Because these classes override the toString function of Object class
    
# Notes Summary:
```
1. without equal, hashcode function if you are using hashMap and want to count occurence of item of a object so it
   would not work 
2. you need to overide equal, hashcode function in the class 
```