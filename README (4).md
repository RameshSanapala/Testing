
# Installation process of Ionic Android App

 Download **android studio** with this link [Android Studio](https://developer.android.com/studio?gclid=EAIaIQobChMI3ZGynLevggMVFqZmAh3ixAuKEAAYASAAEgJ9gfD_BwE&gclsrc=aw.ds)


- [Windows 64-bit Android Studio Download](https://developer.android.com/studio?gclid=EAIaIQobChMIodiN1aCxggMVUwByCh2EwQZnEAAYASAAEgKJJfD_BwE&gclsrc=aw.ds)

- [Mac 64-bit AndriodStudio Download](https://redirector.gvt1.com/edgedl/android/studio/install/2022.3.1.20/android-studio-2022.3.1.20-mac.dmg)

 ## To install Android SDK's

- [SDK tools package for Windows](https://dl.google.com/android/repository/commandlinetools-win-10406996_latest.zip)

- [SDK tools package for Mac](https://dl.google.com/android/repository/commandlinetools-mac-10406996_latest.zip)

![Logo](https://i.ibb.co/HgK7YK4/Screenshot-2023-11-07-153230.png)

![Logo](https://i.ibb.co/8rCqgPZ/Screenshot-2023-11-07-153445.png)

![Logo](https://i.ibb.co/L84xrpT/Screenshot-2023-11-07-153620.png)

![Logo](https://i.ibb.co/MZQc8vM/Screenshot-2023-11-07-154359.png)

![Logo](https://i.ibb.co/hFZjCTC/Screenshot-2023-11-07-154513.png)


## For Java JDK 
[Download Here](https://builds.openlogic.com/downloadJDK/openlogic-openjdk/17.0.9+9/openlogic-openjdk-17.0.9+9-windows-x64.msi)

- After downloading the **Java Jdk** (Java Development Kit ) we have to check that this java jdk is present in environment Variables or not.

## Environmental Variables

To get **Edit the system environment variables** Type **environment** in search bar from your pc.

![Logo](https://i.ibb.co/Tgv97Ft/Screenshot-2023-11-07-162728.png)

Choose **Environment Variables** from System Properties then click **OK**

![Logo](https://i.ibb.co/BfPTNBZ/Screenshot-2023-11-07-163219.png)

In **User Variables** create new variables in capital letters and assign value(Path) to them  as menctioned below and then click **OK**.
- **ANDROID_HOME**
- **ANDROID_SDK_HOME**
- **GRADLE_HOME**
- **Path**

![Logo](https://i.ibb.co/HpKTNzB/Screenshot-2023-11-07-170503.png)

For **New Variables Creation**  

![Logo](https://i.ibb.co/D7VPX11/Screenshot-2023-11-07-163930.png)

Add **new variables** and **values** to them.

![Logo](https://i.ibb.co/Rj8ph3r/Screenshot-2023-11-07-172436.png)

For **Edit Variables** 

![Logo](https://i.ibb.co/rwN23R2/Screenshot-2023-11-07-164604.png)

**Modify the existing variables and values** here.

-Add the **ANDROID_HOME** in capital letters in user Variables as shown in the below and the value we can get from appdata/local/android/sdk 

![Logo](https://i.ibb.co/Yf2M5cJ/Screenshot-2023-11-07-164725.png)

-  **Path Choosing :**

-This Appdata we can Get from press **start+r** to open run now type **appdata**

-**go to appdata** and click on **OK**.

![Logo](https://i.ibb.co/mSbrfV2/Screenshot-2023-11-09-105824.png)

- click on **Local**.

![Logo](https://i.ibb.co/NCrhjrB/Screenshot-2023-11-09-110149.png)

- click on **Android**.

![Logo](https://i.ibb.co/gRPPS5S/Screenshot-2023-11-09-110537.png)

- click on **Sdk**.

![Logo](https://i.ibb.co/TWD40Wg/Screenshot-2023-11-09-110700.png)

- you get the **Sdk packages** here.
- you get the **Sdk Path** as shown in the below.

![Logo](https://i.ibb.co/4mZvSjt/Screenshot-2023-11-09-110455.png)

In **System Variables** create new variables in capital letters and assign value(Path) to them  as menctioned below and then click **OK**.
- **GRADLE_HOME**
- **Path**

![Logo](https://i.ibb.co/W6wjvbF/Screenshot-2023-11-07-170707.png)

For **New System Variables Creation** 
```change this one
![Logo](https://i.ibb.co/D7VPX11/Screenshot-2023-11-07-163930.png)
```
Add **new variables** and **values** to them and click  on **OK**.

![Logo](https://i.ibb.co/Rj8ph3r/Screenshot-2023-11-07-172436.png)

For **Edit Variables** 


![Logo](https://i.ibb.co/rwN23R2/Screenshot-2023-11-07-164604.png)

Modify the **existing variables** and **values** then click on **OK**.

![Logo](https://i.ibb.co/Yf2M5cJ/Screenshot-2023-11-07-164725.png)

- **Cordova :**
**Install** the Android **SDK** and **download** the required tools, platforms, and other components (which is done most easily by **installing Android Studio**).

-**Note :** you **cannot do any Cordova Packages Installation** separately.

## Ionic framework required libraries install using    NPM (node js )






## Installing Ionic

Install the **Ionic CLI**.

```test
npm install -g @ionic 
```
## To Build

```build
ionic build
```
## Use Cordova to build for Android 
- This build is to Generate Android **.apk**

```build
ionic cordova build android
```
## Use Cordova to build for ios
- This build is to Generate ios **.ipa**
```build
ionic cordova build ios
```

## Run an Ionic project on a connected device/Mobile 
```mobile
ionic cordova run android 
```

## Run the App in the browser/Web
```web
ionic serve
```




    
    
## Run Locally

Clone the project

```bash
  git clone 
  https://github.com/nsgprojects/PWD.MobileApk
```
  

