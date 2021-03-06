# Article Analyzer
This Chrome extension uses the API, Text Summarizer, to sum up the key points of an article, and return the number of sentences that the user want for the summary. 

### Setup

Create a folder named "Summarizer Extension" and download the following files into the folder: icon.png, manifest.json, popup.html, popup.js

Type in chrome://extensions in your browser then click 'Load unpacked extension...' on the upper left hand side of the screen

![chrome setup1](http://dab1nmslvvntp.cloudfront.net/wp-content/uploads/2015/04/1428472919chromeextopt.png)

Then select the "Summarizer Extension" folder

![chrome setup2](https://github.com/angievo/screenshots/blob/master/chrome-setup2.png?raw=true)

Once you select the "Summarize Extension" folder, the extension should be added to the list of extensions and a newspaper icon should appear in the top right hand corner of your screen

![chrome-setup3](https://github.com/angievo/screenshots/blob/master/chrome-setup3.png?raw=true)

### Usage 

Go to the page of any article and click on the newspaper icon in the top right hand corner of the browser. Then click "Get a summary now!"

![chrome-setup5](https://github.com/angievo/screenshots/blob/master/chrome-setup5.png?raw=true)

The extension reads in the URL of the current page to summarize its contents or the user can paste in a snippet of text to be summarized. It also includes a feature in which the user can choose how many sentences the summary will be where it says "Type the summarized sentence number you need." The default sentence number is 6. 

![chrome-setup55](https://github.com/angievo/screenshots/blob/master/chrome-setup55.png?raw=true)

Here, the extension returns the summary of this article in 6 sentences

![chrome-setup6](https://github.com/angievo/screenshots/blob/master/chrome-setup6.png?raw=true)


