# FMX-LIKE-INTERLACED-ANDROID-LOADIMAGE
 
**PREVIEW**
![alt text](https://github.com/dondonondon/FMX-LIKE-INTERLACED-ANDROID-LOADIMAGE/blob/master/assets/img/Screenshot_20200904-001234.png?raw=true)

HOW TO RUN ON YOUR PC 
1. **EXPORT DATABASE**
2. **COPY FILE APIImg.php to your xampp (htdocs)**
   for example copy file to *C:\Xampp\htdocs\appru\API\SampleLoadImg\*
3. **CHANGE CONNECTION DATABASE ON APIImg.php WITH DATABASE NAME THAT WAS CREATED ON NO. 1**

   for example
   
![alt text](https://github.com/dondonondon/FMX-LIKE-INTERLACED-ANDROID-LOADIMAGE/blob/master/assets/img/DATABASECHANGE.PNG?raw=true)

4. **CHANGE uRest.pas ON PROJECT**
  change url on source uRest.pas to link / url / directory your APIImg.php, for example *C:\Xampp\htdocs\appru\API\SampleLoadImg\* , 
  so you must change url on uRest.pas to *http://localhost/appru/API/SampleLoadImg/APIImg.php?key=apiapi&act=* Like this
  
![alt text](https://github.com/dondonondon/FMX-LIKE-INTERLACED-ANDROID-LOADIMAGE/blob/master/assets/img/Rest.PNG?raw=true)
