# Why I made this
This entire project was made as a way to make a firebase passion project for myself and others.
Its purpose is to share a free way to use firebase to host static data
I made it because I wanted to try making a hosting project based off a existing repository with firebase.
# Installation
1. First you want to go to the top right and hit the code button
2. Then clone the repository through the various options such as the zip
3. Then run
```powershell
Firebase deploy
```
4. That is it
# Firebase
Though I am not very good with a firebase project I will give you directions on how to use firebase hosting. 
The reason I'm showing you directions is because I was very confused when attempting to utilize firebase hosting. 
## Initialization
> [!IMPORTANT]
> You need to make sure that all of your code is static otherwise this will not work
> If you don't have static code you will need to pay for the firebase blaze subcription to use the app hosting feature
1. To deploy the code you will have to put all of your code in a folder named whatever you want
2. Next you will have to download the `firebase cli`
3. Then you will have to go to the projects directory and run in the terminal or command prompt
 ```powershell
Firebase init
```
4. If it doesn't work then go to the next section otherwise go to step six
5. Then what you will want to do is hit yes if it asks you if you want to initalize below an ascii art spelling `Firebase`
6. Next you will see a few options and what you will want to choose is `Hosting`
7. After that you will have to select if you want to use an existing project or make a new one
8. Then it will ask you what you want to use as your public directory
9. Choose the one that you named the folder over at step 2
10. Next you will have the option to configure it as a single page app making all the urls index.html
11. After you have the option to set up automatic builds and deploys with github
12. Then you will have the option to overwrite your 404.html and index.html if you already have one
13. That is it for the initializaton for the deploy
### Extras
There are extra options you can add on with the firebase deployment while on step 10.
These can add several different features for your firebase website
## Deployment
1. Next you will want to run the command
```powershell
Firebase deploy
```
2. Then you will have to wait a bit
3. Then you will see where your project is being hosted and where the projects console is
4. Your done
> [!NOTE]
> One common issue while deploying is that when deploying something large it may timeout and when that happens it remembers what you already uploaded so you just have to constantly try until it finishes uploading all of the code
# Credits
[Webshare](https://www.webshare.io/) for the proxies\
[Hypackellite](https://github.com/hypackellite/hypackellite.github.io) for the public folder\
[Firebase](https://firebase.google.com/) for the hosting\
[Bedimcode](https://github.com/bedimcode/responsive-404-page) for the 404 page
