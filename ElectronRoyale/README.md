# ElectronRoyale Example
This example illustrates how the [Apache Royale](https://royale.apache.org/) application can be launched as a desktop application using [Electron](https://electronjs.org/).  This example was created with the instructions provided in the blog post [How to create a Desktop Application with Royale and Electron](https://royale.apache.org/how-to-create-a-desktop-application-with-royale-and-electron/).

## Prerequisities
1. Download nightly build (either full or JS-only) of [Apache Royale 0.9.6](https://royale.apache.org/download/).
1. Add the SDK in Moonshine using the following [instructions](https://github.com/apache/royale-asjs/wiki/Moonshine-IDE#add-the-royale-sdk). 

## How to build and launch example
1. Open a console window to the main folder of the application (From Moonshine, you can right-click on project and select Copy Path).
1. Run this command ```npm install --save-dev electron```.
1. If the project is not open in Moonshine already, open the project by double clicking on ```ElectronRoyale.as3proj```.
1. Build project using menu **Project** -> **Build as JavaScript**.
1. In console window run command ```npm start```.
