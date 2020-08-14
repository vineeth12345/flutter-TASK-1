# mediaplayer_app

A new Flutter project
As part of my task i'v made a simple Media Player App using Flutter.Where you can play both Audio & Video From Assets & url.

Prerequisites:

FLUTTER SDK INSTALLED.
ANDROID SDK INSTALLED.
VS CODE (IDE).
ANY ANDROID DEVICE OR AVD.
Description Of Task:

Create Flutter App.
Use Assets (Audio & Video), From which you have to play Audio & Video (Locally From App).
Also Use Audio and Video from Network (url).
Add Buttons like Play, Pause, & Stop. Which should Trigger the Audio & Video When we tap on those buttons.
Step-1: Create a Flutter App using cmd prompt-

flutter create <name of your app>
The Above command Should Look LIke This.
-- After executing this command Flutter will automatically create a Basic Flutter App for you for which we have to modify according to our requirement.

Step-2: Enable HOT_RELOAD Functionality to the App for that we have to make changes to the main.dart File by adding below code.

No alt text provided for this image
Step 3:- Create you home page in home.dart.

No alt text provided for this image
Step 4:- Now to add functionality of audio and vedio in your app you need to add some dependencies in your pubspec.yaml file.

No alt text provided for this image
After adding the Dependencies you should restart your IDE to enable their features.And start building the Features for Audio & Video.

No alt text provided for this image
The above code is for Button events for play, pause, and stop the Audio from the Local Assets.

No alt text provided for this image
The above image is defining the code for the Button events for play, pause, and stop the Audio from the Network and for playing a Youtube Video by intialVedioID.

No alt text provided for this image
No alt text provided for this image
No alt text provided for this image
No alt text provided for this image
No alt text provided for this image
No alt text provided for this image
Since, I added a local asset need to update the pubspec.yaml file.

No alt text provided for this image
This is the complete procedure I followed to built my First APP .

LOOK OF THE APP:

No alt text provided for this image
