
# Ex.No:2 Develop an application that uses GUI Components with Fonts and Colors


## AIM:
To develop an application that uses GUI Components with Fonts and Colors using android studio.

## EQUIPMENTS REQUIRED:

Android Studio(Min. required Artic Fox)


## ALGORITHM:
Step 1: Create a New Android Project:
              • Click New in the toolbar.
              • In the window that appears, open the Android folder, select Android Application Project,
              and click next.
              • Provide the application name and the project name and then finally give the desired
              package name.
              • Choose a launcher icon for your application and then select Blank Activity and then click
              Next
              • Provide the desired Activity name for your project and then click Finish.

Step 2: Create a New AVD (Android Virtual Device):
        • click Android Virtual Device Manager from the toolbar.
        • In the Android Virtual Device Manager panel, click New.
        • Fill in the details for the AVD. Give it a name, a platform target, an SD card size, and
        a skin (HVGA is default).
        • Click Create AVD and Select the new AVD from the Android Virtual Device
        Manager and click Start.

Step 3: Design the graphical layout with a text view and two command buttons.

Step 4: Run the application.

Step 5:On pressing the change font size button, the size of the font gets altered.

Step 6: On pressing the Color button, the color of the text altered.
       
Step 6:Close the Android project. 


## Program:
 ```
/*
Program to Develop an application that uses Font Size using Android Studio .
Developed by: GOKULA PRIYA P
RegisterNumber:  212222040044
*/
```

## MainActivity.java:





## activity_main.xml:

```
<?xml version="1.0" encoding="utf-8"?>
<LinearLayout xmlns:android="http://schemas.android.com/apk/res/android"
    android:orientation="vertical"
    android:layout_width="match_parent"
    android:layout_height="match_parent">

    <TextView
        android:id="@+id/textView"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="30dp"
        android:gravity="center"
        android:text="Hello World!"
        android:textSize="25sp"
        android:textStyle="bold" />

    <Button
        android:id="@+id/button1"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="20dp"
        android:gravity="center"
        android:text="Change font size"
        android:textSize="25sp" />

    <Button
        android:id="@+id/button2"
        android:layout_width="match_parent"
        android:layout_height="wrap_content"
        android:layout_margin="20dp"
        android:gravity="center"
        android:text="Change color"
        android:textSize="25sp" />

</LinearLayout>
```

## Output:



## Result:
Thus, the program for android application, Font Size and color was executed successfully using Android Studio.
