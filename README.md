# unKGS
The un-conventional KGS app.

Look up any active KGS player for receiving some aggregated information at your fingertips!

A no-frills test web app, written leveraging OpenUI5 and metaKGS.  And YQL.


## Features
 - *player's strength* ☆☆☆☆☆☆☆☆ vs *_average_ opponents' strength* ☆☆☆☆☆☆☆☆
 - _friendly_ indicator (greets/thanks after game) ☺
 - Rengo indicator 👥
 - _opening style_ indicators: what player usually plays in the first 4 moves. The most standard moves are recognized: 4-4, 4-3, 3-3, 5-3, 5-4
 - user's picture

  
## How it works

After loading up the OpenUI5 framework (about 500 KB), it presents a clean screen with an input field to specify the username you wish to query.
The query submits a request to the archives page via metaKGS, and drills down, parsing up to two games in order to extract some more information.


## How to install

Just copy the main application file (unKGS.html) wherever (pc/mobile device), along as the img/ folder and the files therein contained, in the same folder as the main application file.  This is a pure HTML5 app so it should run anywhere.


How to download the main application file unKGS.html from GitHub:
1. Go to the unKGS.html file
1. Click it to view the contents within the GitHub UI.
1. In the top right, right click the Raw button.
4. Save as

Next, create an "img" folder.

Finally, download the images in the img folder.

## Endpoint

The app has also been published by @kgsnick at:
 - http://unkgs.kgsnick.ru/


## External libraries used and references

### UI
 - [OpenUI5](http://openui5.org)
 
### API
 - [metaKGS](https://metakgs.org) https://github.com/anazawa/metakgs.org
 - [YQL](https://developer.yahoo.com/yql/)

## KGS Go Server
 - https://www.gokgs.com
 - [KGS Archives](https://www.gokgs.com/archives.jsp)

## Learn to play go
 - [The interactive way to go](http://playgo.to/iwtg/en/)
