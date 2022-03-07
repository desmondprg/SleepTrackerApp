--Readme document for Maika Marin, maikam@uci.edu, 95631171--
--Readme document for Desmond Garrido, dgarrido@uci.edu, 78457276--

1. How many assignment points do you believe you completed (replace the *'s with your numbers)?

*/10
- */1 The ability to log overnight sleep
- */1 The ability to log sleepiness during the day
- */1 The ability to view these two categories of logged data
- */2 Either using a native device resource or backing up logged data
- */2 Following good principles of mobile design
- */2 Creating a compelling app
- */1 A readme and demo video which explains how these features were implemented and their design rationale

2. How long, in hours, did it take you to complete this assignment?
60 hours


3. What online resources did you consult when completing this assignment? (list specific URLs)
https://stackoverflow.com/questions/52801814/this-syntax-requires-an-imported-helper-but-module-tslib-cannot-be-found-wit
https://ionicframework.com/docs/api/radio
https://www.w3.org/TR/NOTE-datetime
https://forum.ionicframework.com/t/refusing-to-run-ionic-cordova-plugin-inside-a-capacitor-project/198408/2
https://ionicframework.com/docs/api/list
https://stackoverflow.com/questions/45894387/html-ionic-3-x-how-to-use-a-for-loop-in-the-html-file-using-in-instead-of-of
https://ionicframework.com/docs/api/modal
https://ionicframework.com/docs/v3/api/components/modal/ModalController/
https://www.youtube.com/watch?v=Bs_NnfyRFmk
https://fonts.google.com/specimen/Inter?preview.text=Not%20sure%20where%20to%20go%3F&preview.text_type=custom#standard-styles
https://stackoverflow.com/questions/45670752/ionic-how-to-wordwrap-a-long-string-in-ion-header
https://capacitorjs.com/docs/apis/storage


4. What classmates or other individuals did you consult as part of this assignment? What did you discuss?
N/A


5. Is there anything special we need to know in order to run your code?
When running the app through ionic lab, the colors in the global css will be affected by the computer's color options. My partner and I noticed, that if I had my computer on dark mode, the colors would come out incorrectly. 
In order to see the app in it's intended view, please change the computer's color settings (start >> settings >> personalization >> colors >> chose your color >> light).


--Aim for no more than two sentences for each of the following questions.--


6. Did you design your app with a particular type of user in mind? If so, whom?
Yes, we designed our app to cater specfically to college students and working professinals who'd be interested in loggin and tracking their sleeptime and sleepiness.


7. Did you design your app specifically for iOS or Android, or both?
We designed our app specifically for iOS.


8. How can a person log overnight sleep in your app? Why did you choose to support logging overnight sleep in this way?
A person can log overnight sleep in our app by clicking the "Enter Sleep Time" button at the bottom of the page which will pop up a Modal and the can submit their time through a date picker. We designed it this way because a pop-up Modal is a quick and easy interface for user to enter data quickly and exit out of it.


9. How can a person log sleepiness during the day in your app? Why did you choose to support logging sleepiness in this way?
A person can log sleepiness during the day by clicking the "Enter Sleepiness" button which will pop up a MOdal and where the user can clikc their number through radio buttons. We designed it this way because radio buttons make it an easy way to choose one options and prevents a user from clicking more than 1 number.


10. How can a person view the data they logged in your app? Why did you choose to support viewing logged data in this way?
A person can view the data they logged on the main/home page where  it is separated by Sleep Time data and Sleepiness data and in chronilogical order. We decided to display the data at the home page because it will be the first thing a user sees when launching the app and separting the two different types of data will help users better to differenciate and find the data they are looking for.


11. Which feature choose--using a native device resource, backing up logged data, or both?
The feature we decided to use was backing up logged data on Ionic Storage from cordova-sqlite-storage.


12. If you used a native device resource, what feature did you add? How does this feature change the app's experience for a user?
N/A


13. If you backed up logged data, where does it back up to?
In the ionic storage, specifically in sleep.service.ts, it is stored in the storage variable declared in the constructor.

14. How does your app implement or follow principles of good mobile design?

Our app implements good mobile design by having a useful initial view that displays the current time and the loged data of the user as well as a navigation bar on the bottom for our different screens. In addition, we have - 
an "uh oh" feature implemented where if a user accidentally presses a button to go to a page they didn't want to, they can simply press the "x" on the top left of the page to exit out. 
Furthermore, the text size on our screen is readible to all users and once a user enters in overnight sleep or sleepiness data, the app will provide feedback to the user that the data was submitted and can be seen on the home page so the user knows that their data was correctly entered.
