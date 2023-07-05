﻿# ImageDownloaderFromJsonUrlArray

(first, make sure you have node installed on your computer)  

to install the necessary packages, open up your terminal and run this command:  
```
npm i  
```
Put your URL links to images in **imageUrls.json** file in the same order as I have in the template, you can add any number of URLs as you want,  
if you have a node version prior to **version 18** then install node fetch as well with this command:  
```
npm i node-fetch 
``` 
then import it inside index.js:  
```
import fetch from "node-fetch";  
```
start up your node server with this command:  
```
node index.js   
```  

- Enter 1 to enable the duplicate URLs filter else enter any number to disable the duplicate URLs filter.  
- Enter the width in pixels (aspect ratio for height will be maintained)  
- Choose the available formats for the output,

Check your downloads folder for downloaded images and make sure to put already downloaded images in a separate folder to avoid overwriting   
(as files are downloaded in selected format with name as -> index of the iteration number in loop)

> This tool is cli based that will be helpful for web developers. Combined with random image-providing tools such as picsum (as in imageUrls.json), this tool can be of great use to generate dummy images of specific formats, such as next-generation formats like webp that are lighter in size
