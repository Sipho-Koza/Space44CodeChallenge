# Space44CodeChallenge

Good day, my name is Sipho Ncedo Koza from South Africa. 
This is my code challenge application.

I figured that I can not be able to finish the unsplashed app that you guys gave me, so I opted to send you an app that I created for fun back in 2019.
The app is far from finish, but it has a structure and architecture that one could see the kinda code I write.

The name of the app is called TV Maze, I created this app because TV Maze has a free API that they exposed to the public to consume, hence I took an adbantage of that.

TV Maze app is a tab bar applicatin, that consist of 5 tabs: (Schedule, Shows, Poeple, Network and Developer Profile Tab)
  * Only Schedule tab has UI and funcatinal code.

The purpose of the app was to develop an app that gives viewers a schedule of shows that TV Maze is offerring.

Schedule tab gives a list of shows. on each cell it has an avatar of the show, the name, airing time, duration, channel, and the type of the show.
When you click on the cell or item on the list, you get navigated to the details screen of the show where you will see more information about the show.(details screen not done)

Language used: Swift
IDE: Xcode
Design Pattern: MVVM

The list of schedule has a custom cell.
The app compoments where created using code.


Builder Folder create the componenst, the navigation controller, tabbar and images used on the tabbar
Utils folder had reachability code which I copied from the internet, and the activity indicator code which is not done as well.
Webservice folder has ServiceClient code that has generic fetch service call method, client api code for your base path and resource file to specify your http methods.

Models folder has schedule model thats structre the schedule model from teh api
Extensions folder has all the extended componets that I want to specify to meet my apps design (Color, Font, Strings, buttons etc)
ViewControllers folder has all the functional folders for all 5 tabs i have on the app.

images and icons are on the assets folder.

Pods used: Kingfisher ~ for retrieving images and store them 
         : NVActivityIndicatorView ~ for loading indicator when making a service call 
         
So when wanting to run the app, please do pod install / pod update if you have pods install in your pc already.
