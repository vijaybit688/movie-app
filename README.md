HI
This is a Movie app

Flutter Version Used :-

* Flutter 3.27.4 • channel stable • https://github.com/flutter/flutter.git
* Framework • revision d8a9f9a52e (6 weeks ago) • 2025-01-31 16:07:18 -0500
* Engine • revision 82bd5b7209
* Tools • Dart 3.6.2 • DevTools 2.40.3

I had used public movie api
https://www.omdbapi.com/


This app is created using GetX as a state management and it follows MVVM Folder Structure.
I have followed the Clean Architecture pattern in Flutter, ensuring that every file is well-organized and structured.


This app contains 5 Screens

1. Splash Screen
   - The user will auto navigate to DashBoard after 2 sec

2. DashBoard Screen
   - It has bottom navigation bar 
   - And it manages the tabs
3. Home Screen
   - In this screen i had integrated the movie list api
   - I had handled the horizontal and vertical scroll in this screen
   - I had added code for network connection check also
   - From this Screen the user can navigate to details page of any movie by 
     clicking on any on the movie on the Home Screen
   
4. Search Screen
   - In This screen i had integrated the search api 
   - And when the user will stop typing then only the api will be called 
   - And the user can navigate to particular movie by clicking on a search result
   
5. Movie Detail Screen
   - In This Screen Details of the selected movie is shown to the user in different screen


 
