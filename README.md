# Sport Asthma
## Installation
This respository contains an ISO image named ```Sport Asthma``` that will install the Windows XP software to run an EVH testing application.

Download the Sport Asthma file to your local hard drive.

To create an install CD from the ISO image follow the instructions relevant to you operating system:

Windows 7:

http://windows.microsoft.com/en-gb/windows7/burn-a-cd-or-dvd-from-an-iso-file

Windows 8:

1. Open the folder where you have saved the ISO image
2. Right-click on the ISO image and select ```Burn disc image```

Windows 10:

1. Open the folder where you have saved the ISO image
2. Click on the ISO image
2. On the top of the screen of File Explorer click ```Disc Image Tools -> Manage```
3. Click on ```Burn```
4. Select your CD as Disc burner and click on ```Burn```

Run the installation disc and click ```Install``` on the Splash Screen

The application will install EVH Tester to ```C:\Program Files\EVH Tester\```

A required dependency for the EVH Tester application is Cardinal Health MicroPCActiveX, which will install to ```C:/Program Files/Cardinal Health/ MicroPC ActiveX```

During the installation you will need to input the MicroPC Serial Number ```170 022 161``` on the Registration Page.

When the software has completed installing close the Install dialogue box and Quit the Splash Screen. Then:

* Navigate to ```C:\Program Files\EVH Tester```
* Right click on the ```EVH tester``` file and select ```Send To -> Desktop (Create shortcut)```
* Right click on the shortcut icon created on the Desktop and select ```Properties```
* In the ```Target``` field edit the path to read ``` "C:\Program Files\EVH Tester\EVH Tester.exe" -nolicense```
* Click ```Apply```
* Launch the EVH Tester application from the Desktop shortcut

##Configuration
The first time you run EVH Tester you will probably want to configure the testing options. To do this go to ```Tools -> Options```. 

### EVH Protocol
You are able to configure **_EVH Test Options_** and **_EVH Post Test Options_**

1. **EVH Test Options**

  * *Rolling Avg Duration* (default 6s) refers to the smoothing of the realtime ventilation trace. A very short duration will result in a 'spikey' trace while a long duration will take longer for changes in ventilation to be displayed.
  * *Test Duration* (default 36s) refers to the ength of time the EVH test lasts.
  * *Target Tolerance* (default 10%) refers to the acceptance range for spirometry tests. Repeated tests will have to be within this range in order to be accepted.
  * *Significant Value* (default FEV1) refers to the measure against which the acceptance criterion in assessed.

2. **EVH Post Test Options**
You are able to set the number and timings of the post-challenge spirometry tests (these are in seconds from the end of the test).

###Bronchodilator Challenge
You are able to set the number and timings of the post-challenge spirometry tests (these are in seconds from the end of the test).

###Spirometry
You are able to configure the **_Spirometry Test Options_**

1. **Spirometry Test Options**
Select the spirometry measures that you would like to appear on the patient report.
