# SWUSK1
Phase 1

1.INSTALLATION - Follow these steps:
    a. Ownership of the website will be transferred to the intended administrative Google account, by the developers for 
      initial release.
    b. (Note: In order to integrate the Bookeo Widget into a Google Site, the owner of the account must submit an email
      to the Bookeo support team (help@bookeo.com), requesting that the feature to test for widget 
      presence on the target website is disabled. In the experience of the developer, this only took a few hours wait for a
      response and was never denied.)
      The embedded gadget on the website will be updated to point at the administrator's account. This involves going to  
      the page editor, clicking edit page in the top right corner, clicking on the Google Gadget labelled Bookeo Online   
      Appointment Scheduling, clicking the properties button (shaped as a gear), and updating the "Account id" field with the    
      administrator's Bookeo account id. This id can be found in the administrator's Bookeo account, under Settings and Web site 
      integration, from field 1. A line similar to the following - <script type="text/javascript"                 
      src="https://bookeo.com/widget.js?a=XXXXXXXXXXXXXXXXXXXXXX"></script> - will be found, where the X's represent the account 
      id. The installer only needs this id. The installer will press OK, in the bottom left corner of the active window, and  
      then SAVE, in the top right corner. The administrator's Bookeo account needs to be updated as well. Under the Settings tab   
      in the Bookeo account, click Web site integration. In the field labelled 2 , copy and paste the following link
      https://sites.google.com/site/estudiobooking/ . Then click OK. 
    c. The administrators Bookeo account is edited in the following ways
        i. Under the Settings page in the Bookeo account, click Colors and Styles. In the Page tab, under Colors, select image
           from the drop down menu next to Background. Click Upload and select transparent_image.png from the provided files. 
           Copy the following into the next two boxes - #02307D, and #A7EBC4 into the third.
        ii. Click the Box tab, also under Colors, select custom color from the drop down menu next to Mode:. In the following  
        three boxes enter the following values in the order listed here - #A7EBC4 , #02307D , #642B8A. 
        iii. From the provided files, open ###### and copy the entire file into the box at the bottom of the same page, 
        labeled Custom CSS (advanced).
        iv. Click OK near the top right of the page. 

2.USAGE - If changes are desired, it is strongly advised that they are implemented by someone with prior knowledge of CSS.
  Otherwise, color values can be changed under the Settings and Colors and Styles area of the administrator's Bookeo account. 
  Use of Bookeo continues in the same manner that it done prior to the update. 
