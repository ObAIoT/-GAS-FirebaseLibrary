# -GAS-FirebaseLibrary
A Google Apps Script library and a demo script for Firebase access
This is a revision from the original source under the Apache License, Version 2.0
https://sites.google.com/site/scriptsexamples/new-connectors-to-google-services/firebase/source
Here are the main revisions: 
1. Besides getAll; add setAll for bulk data write to database.<br/>
2. Add exception handling for exceeding UrlFetchApp quota limit.  <br/><br/>
 
# Source codes
* Library Id: MxGFqRot3O658Y-B8q2SkCeoUuG5-a_8Z
* Library source: https://script.google.com/d/1VkaZf_Y8DJnC-9GdkGr5eA7eOZ8l1g8CSP7U_2MYfac97pHZEqK01za1/edit
* Demo script: https://script.google.com/d/11SDhxP53ROEvXstSioHDAl3pDNUIb3prfNRUoHhv8E1DvFu0snf56UHN/edit?usp=sharing
  Be sure to text in your own Firebase url and secret in Firebase_.gs file <br/><br/>

# Notices
* Add as a library or put source code in your GAS project for faster operations<br/>
* Please do use setAll and getAll as best as you can beacuse a quota limit of "UrlFetchApp" present not only for daily counts but also for frequency in a certain period. 
  You may get an exception "Error: We're sorry, a server error occurred. Please wait a bit and try again." which results from exceeding quota limit.<br/>
