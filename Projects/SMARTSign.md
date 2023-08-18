# SMARTSign Project

[Client's Original Site](http://storage.googleapis.com/smartsigndictionary.org/index.htm)

![SMARTSignDemo](https://github.com/ayersdecker/Notebook/assets/69859630/dcc1c890-1cca-4f52-b4e0-7f0595b9e2e1)<br>
*Demonstration of New App*
## Goal
The new application aims to replicate the work done on the original site along with an updated search function. 

## Current Status of Project
The mobile application has finished technical development. The Logo and SplashScreen need to be added , then the product will be packaged and sent back to client.

## Framework 
Microsoft .NET MAUI (C#/XAML)

## Target Platforms
- Android
- iOS
- Windows 10-11
- macOS

## Findings from UX Evaluation

### Current Website Issues

*   The application does not function beyond it being a clone of the YouTube Channel. User’s will (soon) have the ability to click on a desired picture, and the corresponding video will take its place. 
    
*   Loading videos is a bit glitchy, especially from a new search.
    
*   The names of each video are strange, with some naming schemas not friendly for users who are viewing the application. (Names from the YouTube channel)
    
*   Pictures of videos are very inconsistent or missing. Many videos load without a unique thumbnail. Not all videos contain thumbnails.
    
*   Thumbnail selections also contain potentially sensitive or biased information.


### Considerations / Demographic: 

*   Target Demographic (from UX assumption), would be parents or new signers who wish to translate an English Word/Concept they know into ASL
    
*   This application is friendly to Hearing, Hard of Hearing, and Deaf individuals who have average or above sight levels. Is not Deaf/Blind Friendly (which is ok).

### Potential Changes / Upgrades:

- - [x] Moving the search bar is a design pattern used in many other applications. This will also shorten the user flow, preventing the need for the search bar toggle to resume a new search.
    
*   Autoplaying videos (once pictures are clicked) to hide the iFrame that renders with each video. 
    
*   Adding a Link to the YouTube channel or other information within the application. 

- - [x] Subtracting the video titles (possibly), but would cause issues with the videos that exist without thumbnails.
    
