
__Test Integration:__ TEST-IntegrationFile.2cf3ec...e079.btin
__Folder:__ Desktop >> VIN_Test

First thing first, if you are not testing the printed look just an idea. Go to a printers properties and pause the printer. This will allow you to print to a file instead of the printer. 

This will save you a lot of time and paper.  You can also use the BarTender History Explorer to see what the label will look like.  This is a great tool to use when you are testing your label.  You can find the BarTender History Explorer in the BarTender folder in the start menu.  

When done clear the printer queue and unpause the printer.
  
  ### Steps:
  + Make the change you want to experiment with SmpleTrigger2.dd and save it.
    + Or make your own .dd file
  + Copy and paste the .dd file into the scan folder
    + The scan folder is located in the VIN_Test folder
  + When you do this the file will be automatically scanned and changed to a .dat file
  Check it out in the BarTender History Explorer
  #### If the file does not change to a .dat file
  + Open the BarTender Integration Builder
  + Click on the "Open Integration File" button
  + Navigate to Desktop >> VIN_Test >> TEST-IntegrationFile.2cf3ec...e079.btin
  + Click on the "Open" button
  + Click on the "Test" Tab
  + Click on the VinLabel-12-27-22 in the "Integration" box / section on the left
  + Click on the "Run" button
  + THEN BAM WORKING