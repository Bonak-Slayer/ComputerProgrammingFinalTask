# ComputerProgrammingFinalTask
An app for flights, made by Karl Reuben Resultan

IMPORTANT NOTES
I divided the project into two applications. The reasoning behind this is that it wouldn't be as safe to let the end users access
the administrator side by guessing the password for the Admin user and also, since I already made loads of controller classes,
it's taking a toll on the runtime of the app. I can optimize the code to reduce the fxml files and controller classes needed
but it is what it is.

In order to play the videos (on fxml files that were made specifically for doing so), you have to specify in the
corresponding controller class the path of the video. (In my case, I saved it in C:\Users because java won't read the file
since my username in my computer was Lord Geese and spaces in the said username wasn't respected by the mediaview control in scenebuilder)

Keep in mind that you also have to save the said videos in that directory or else the video won't play and the app won't proceed to the next
window because the video has to end (I overrode the run method).


javafxapplication11 was the accidental name of the End User application and I didn't really pay attention to changing it because I was
quite busy with making the assets of the application (The videos, animations, gif files, images were all made by me).

At some point, I considered renaming it because it did bother me but refactoring it would mean that I would have to recheck
if all other classes referencing the class was correct. So, I just let it be lol

