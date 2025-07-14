# Steps to add email signature to Outlook Online
__Swapping to or just using the new Outlook for the web?__ \
Let's add your email signature to the new Outlook for the web. \
After you log in to Outlook for the web, follow these steps: \
1. Click on the **Settings** gear icon in the top right corner of the screen. \
![Settings Gear Icon](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepOne.png)  \
2. In the Settings menu, click on  **Account** >> **Signature** \
 2a. It could be easier to find the code in later steps to add a short text in the text box. \
![Account Signature](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepTwo.png)  \
3. This part is awkward because the signature editor is not very user-friendly. Left-click **OUTSIDE** the text box, then click the **inspect** menu item. \
![Inspect Element](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepThree.png)  \
4. Now you will be a coder for a moment. In the developer tools, find the "Element Selector" icon (a cursor inside a square) and click it. \
![Element Selector](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepFour.png)  \
 5. Click on the edge of the text box where you add your signature. This will highlight the HTML code for that element in the developer tools.  \
 ![Highlight Element](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepFive.png)  \
6. In the developer tools, click on the arrow to "open" the highlighted element. \
![Edit as HTML](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepSix.png)  \
6a. This will show you the HTML code for the signature box. Right-click on the highlighted code and select **Edit as HTML**. \
![Edit as HTML](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepSix2.png)  \
7. Now you can paste your HTML signature code into the text box that appears. Make sure to replace any existing content. \
![Paste HTML Signature](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/StepSeven.png)  \
8. After pasting your signature code (replacing the <div> to <div> with <table> to <table>), you can close the developer tools. Then, click **Save** in the Outlook signature settings. \
![Save Signature](https://raw.githubusercontent.com/Karavan-Trailers/How-To-Sheets/main/img/esig/webOutlook/fin.png)  \
9. Your email signature is now set up in the new Outlook for the web! You can test it by composing a new email and checking if your signature appears as expected. You should see your signature in the email body, complete with any images or formatting you included in the HTML code. \
10. Change your menu options For new  messages and Replies/forwards to your new signature.
