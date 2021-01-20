# Unsubscribe-Youtube-Channel-Auto-Bot
Mass Unsubscribe Youtube Channel

The following method mass unlike from all videos you’ve like. So if you have a video that you may feel you might forget after you unlike or that you don’t want to unlike from them either take note of the few videos that you want to maintain a likes and then proceed with the method below.

---------------------------

INSTRUCTIONS

1. Log on to your youtube channel. Click on your youtube channel profile picture then click “My channel.

2. Now click on “Like videos” which is situated at the left. Click on "Edit".

3. Next, simply right-click anywhere on the page and then click the option to Inspect Element (or just Inspect).

4.  Click the Console tab.

-----------------------------

4. Now, simply copy-paste the below “code” into the Console. Once you’ve copied and pasted it into there, just hit your Enter key

------------------------
var items = $('body').getElementsByClassName("pl-video-edit-remove-liked-video");
for(var i = 0; i < items.length; i++){
items[i].click();
}

-------------------------------------- 

That’s it!. copy and paste the code to do it again.

------------------------------------
