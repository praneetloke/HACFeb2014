HACFeb2014
==========

A repository for challenge participants of Hangout and Code to create a pull request against for their submissions.


Challenges (from 9AM on 2/25/14 to 9AM on 3/3/14)
----------
*(in no particular order, although it would be easy for you to follow the order)*
- Fork this project to your own github account.
- Create an Android project using Android Studio with the package name com.helloworld and app name HelloWorld.
- Add an Activity, with whatever navigation type (or even no navigation type), to the app. You may call it whatever you want.
- Change the title/label (not the filename) for the above activity to something other than the default name.
	- Change the name in manifest file.
	- What is the other way of changing the title/label of an activity? Add a comment in the manifest on how to do this. Pasting a link to a website (preferrably Android's docs) on how to do this is acceptable.
	- BONUS criteria: Using a string resource instead of hard-coding the name will put you ahead of the rest.
- Add a Login Activity using the wizard.
- Change the starting activity from the first Activity to the Login Activity. (**Hint**: which xml file holds the app's metadata?)
- You learned about starting an Activity from one Activity. Now, use the Login Activity to start the other activity upon successful password match.
	- The wizard-created Login Activity has some sample code to simulate a fake authentication. It does this authentication instead an AsyncTask class. (**Hint**: The ```doInBackground()``` executes first in this particular asynctask and the return value of this method is passed on as the result to ```onPostExecute()```.
- BONUS criteria: Show a Toast notification upon successful login. (**Hint**: we saw how to show a Toast notification during our session.)

To win
------
- **You must be a Centric Consulting employee, must have attended the 2/20 session either physicall or virtually.**
- Be the first to create the pull request with the above tasks completed.
- If you are the first to create the pull request with the above tasks completed, but, someone creates a pull request after you by completing more (or all of the) bonus criteria items (correctly) than you have, then they have a higher chance of being chosen as the winner.
	- I said *chance* of being the winner because you could complete everything but may have done something incorrectly so I'll have to evaluate and pick the winner.
- If you completed all of the bonus criteria and are the first to create the pull request as well, but someone else creates a pull request after you and also completes all of the bonus criteria, then the winner will be based on correctness.
	- In otherwords, **completing all of the bonus items and creating the pull request first does not automatically make you the winner**.
- Evaluations will be done on 3/3/14 and the winner will be announced as soon as possible after that.
