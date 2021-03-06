                                    Countries information application



Android application that shows list of countries and detail of a country chosen.

Architecture: [Model View Presenter](https://en.wikipedia.org/wiki/Model–view–presenter).                         
Network Library: [Retrofit](http://square.github.io/retrofit/)                                                                 
Image Library:  [Universal Image Loader](https://github.com/nostra13/Android-Universal-Image-Loader)                           
Async communication: [Otto Event Bus](http://square.github.io/otto/)                                                           
Dependency Injection: [Dagger 2](https://github.com/codepath/android_guides/wiki/Dependency-Injection-with-Dagger-2)           

![alt txt](https://github.com/gurappa/Countries-Info/blob/master/Countries_mvp.jpg)



Improvements:
1. Alternative layout for Tablets. Fragments are modular and Activities/Fragmens combinations are well placed so should be easy.
2. Currently app uses different retrofit service instances for each URL, one for Countries API, one for Details API. Should be able to use only one retrofit instance.
3. Adding image transition from countries screen to details screen.
4. To handle for no network scenarios.
5. A splash screen.
