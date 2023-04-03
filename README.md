ReadMe_Instrutions


1. Open the Project folder and go to "\Test_Automation_Project_ePay\driver\" and take "chromedriver.exe" and place the file into a user system any drive path.
2. Copy the user system drive path and paste the value to

"\Test_Automation_Project_ePay\src\main\java\core\ui\UiClient.java"

chromeOptions(){
System.setProperty("webdriver.chrome.driver", "<Chromedriverpath>");
}
paste the value in "<Chromedriverpath>"

3. Goto 

"\Test_Automation_Project_ePay\src\test\resources\features\demo.feature"

and Run the Cucumber BDD file to see the execution for 4 scenarios provided.

4. Added Test Screenshots in "\Test_Automation_Project_ePay\screenshots"

5. Added Requirement document in "\Test_Automation_Project_ePay\requirementDoc"

