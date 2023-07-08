# Lock Screen
-----
Since I prefer to have my hands on the keyboard more then a mouse, I needed a quick and easy way to lock my Mac before I stepped away. I've used a screen Hot Corners in the past to enable my screensaver, which in turn locked my Mac. However, there were times I or others accidentally navigated to the Hot Corner and locked my Mac. So, now with Lock Screen I don't have to worry about a Hot Corner potentially inadvertently locking my screen. Now I can simply enter `Lock` in Finder and quickly step away for a fresh cup of tea.

## Getting Lock Screen
[Release 1.0](https://github.com/scriptmunkeeofficial/lock_screen/releases/tag/1.0)

## Installing Lock Screen
After downloading Lock Screen, follow the steps below to install the app.

1. Open `Finder`
2. Navigate to your Home folder
... In `Finder` select **_Go_** and then **_Home_** from the **_Menu Bar_**
3. Create a new folder called `Applications` if it doesn't exist
4. Locate the Lock Screen zip file you downloaded and unzip the file
5. Move the `Lock` app to your `Applications` folder in your Home folder

## How to use Lock Screen

Before using Lock Screen you must enable your Mac to require a password when it wakes up.

1. Open System Preferences
2. Select Security & Privacy
3. Under General, check the box for "Require password" and leave immediately select in the drop down
4. Enter your password if prompted

### From Finder

```
Press Command + Spacebar
Type: lock
```
![Lock From Finder](/resources/lock_from_finder.png)

### From the Terminal

```
open -a lock
```
![Lock from Terminal](/resources/lock_from_terminal.png)
