Whenever a new activity is created , in the AndroidManifest.xml, 
a new line is added, containing the activity itself (with its name)
example : <activity android:name=".Main3Activity" />
The most recently created activity will always be on top of the activity stack,
when a new one is created ,it just pushes the old one down.