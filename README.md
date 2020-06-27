# Unity-OculusQuest-Template
Starting a Unity project that uses the Oculus Quest requires a lot of processing time and careful steps/instruction. Finding the correct compatible combination of Unity editor versions and VRTK versions is also time-consuming. To save you and me time, here is a pre-configured, working Oculus Quest Project for starting new projects. 

I use Unity 2019.4.1f1 and VRTK 3* (from the asset store). As for Oculus Integration, I downloaded the latest version right now (version 17.0) to the project. 

Here are the steps to starting: 

1) Clone this repository. 

2) Download Unity 2019.4.1f1 or upgrade this project to a newer version of Unity. Make sure you follow the instructions here: https://developer.oculus.com/documentation/unity/book-unity-gsg/

3) Go to Oculus Developer and create an application. Save the application ID for step 5. 

4) Open the project and the "Test" scene in Assets. 

5) In the task bar, go to Oculus -> Platform -> Edit Settings. Paste your App ID into the "Oculus Go/Oculus or Gear VR" field. Login using your Oculus Developer credentials. 

You should be ready to go after that!

\* I'll be changing it to VRTK 4 when it comes out of beta. Right now it causes too many compilier errors when combined with the Oculus Integration package. 
