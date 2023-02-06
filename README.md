# **Xcode14 Default themes** &nbsp; [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vbaswin/Xcode14-VScode-Extension)
<br>

_The default themes in Xcode14 is __something...___  
I was not able to find themes that could rival it in vscode marketplace.  
Hence I created my own. It is identical to default themes in xcode.  
Hope it helps other programmers who also like Xcode themes.    

This extension consists of both **dark** and **light** mode

#### **Contents**

- [ScreenShots](#dark-theme)
- [Installation](#install-instructions)
- [Preferred settings](#preferred-settings)
- [Override color Scheme](#override-color-scheme)
- [Repo link](#repo)

<hr>


## **Dark Theme**
<br>

![Dark theme png](/dark.png)<br>
<br>

## **Light Theme**
<br>


![Light theme png](/light.png)


<hr>

# **Install instructions**
<br>

### **1. Through Extensions**

- Open extensions in the activity bar 
- Search for Xcode14-Default theme
- Click install
- Select the required color scheme (dark or light)

### **2. Directly through market place** 

- Go to https://marketplace.visualstudio.com/items?itemName=AswinVB.xcode14-default-themes
- Click install
- You will be redirected to VSCode automatically
- Click install 
- Select the color scheme (dark or light)


<br>
<hr>

## **Preferred settings**
<br>

- Xcode uses SF Mono Medium as the primary font 
- If not present in your system install from https://developer.apple.com/fonts/
- Copy the corresponding code depending on light or dark theme  
<br>

- for **Light Theme**
```
"editor.fontFamily": "SF Mono, Regular",
``` 
<br>

- for **Dark Theme**
```
"editor.fontFamily": "SF Mono, Medium",
``` 

<br>

- Bracket pair colorization is not present in XCode  
- To disable it copy the code below

```
"editor.bracketPairColorization.enabled": false, 
```
<br>

- Place the copied code in [settings.json](#find-settingsjson-file) File
<hr>


## **Override Color Scheme**
<br>

###  **To remove scroll bars (both horizontal and vertical) and always show minimap slider**
<br>

- Copy the code below

    ```
    "editor.scrollbar.horizontal": "hidden",
    "editor.scrollbar.vertical": "hidden",
    "editor.minimap.showSlider": "always",
    "editor.scrollbar.verticalScrollbarSize": 0,
    "editor.scrollbar.horizontalScrollbarSize": 0,
    ```
- Place them in [settings.json](#find-settingsjson-file) file.

<br>
<hr>

## **Find settings.json file**
<br>

- Open command palette using <br>
    ```ctrl + shift + p``` &nbsp; &nbsp; in WINDOWS<br>
    ```cmd + shift + p```  &nbsp; &nbsp;in MAC
- Search for 'Open User Settings (JSON)`  

- Paste the copied code inside below any line (don't go outside the parent {} brackets)

<br>


<hr>

# Repo

[![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com/vbaswin/Xcode14-VScode-Extension)
<br>
=> Open to contributions 😁
