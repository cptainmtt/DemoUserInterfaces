# Auto Update Module

This JavaScript module allows you to implement automatic GUI updating features into your projects.  
This way you can store your guiDesigner projects in dropbox (or similar) then any time the project GUI file (or project archive) changes, you can present a notification to ask the user to update or ignore the update.

## Usage

Simply add the autoupdate.js file to your project and instantiate it in your own main.js file for your projects.  
You can can use the main.js file included in this demo as a sample on how to use it within your projects.

## Recommended Project Storage

We recommend either using your own web server to store the project, or a service like DropBox.  
Always use project archives (zip files) when storing on services like dropbox to ensure asset files for your GUI will be loaded correctly.

## Demo

Download the project via the below URL and add your iViewer license to the project in guiDesigner, then load it onto your licensed device running iViewer:  
http://cmdf.us/autoupdater