Explain what is a Framework and What kind of framework you have used?
What are the Locators available in Selenium?
Implicit vs Explicit wait and which should be preferred over other
What is the difference between Absolute Path and Relative Path?
What are the types of waits available in Selenium WebDriver?
How to input text in the text box using Selenium WebDriver?
How to switch between frames in Selenium?
How To Perform Right Click Action (Context Click) In Selenium WebDriver?
What type of scenarios cant be automated using selenium
How do you prevent security breach when password is getting exposed in Automation execution report ?
How do you do parallel testing of test cases in Selenium ?
How do you rerun failed test cases in Selenium ?
What is GitHub and Jenkins?
What is cucumber in selenium?
How to set priority in TestNG? 
How to perform parameterized testing in TestNG? 
How to mouse hover on a web element? 
How do you write an Xpath locator to identify paragraph elements that are the immediate child of a div element, or the descendent of a div element?




find the weblement of that test box the use sendkeys method to pass the text.

How to switch between frames in Selenium?
to switch focus between frames  we use
driver.switchTo().frame(by id,name,webelment)

How To Perform Right Click Action (Context Click) In Selenium WebDriver? 
find the web elment then use mouse action from action class
Actions act = new Actions(driver);

act.ContextClick(wb).build().perform()


What type of scenarios cant be automated using selenium 

Privileged Access Management: Use PAM solutions to control access to sensitive systems and data, limiting it to authorized users only.
Multi-Factor Authentication: Add an extra verification step with MFA to significantly increase account security.
not pass password and username drictly storing them in differnt layer and passing them

How do you do parallel testing of test cases in Selenium ?
with the help of surefire pugin in terms of BDD framewor

and in terms of testng we use parallel in xml file and we need to proide threadpool sixe

How do you rerun failed test cases in Selenium ?
while using testng we get directly the failed testoput folder in which all failed testcase are there
or use iretry interface .

in bDD use Rerun plug in and create another testrunner class then run it.

What is GitHub and Jenkins? 

github is online reposotry to maintain and manage the sourcecode which also tract the changes.
jenkins= it is tool to automate the build and deploy the source code in reqire envirnment and it also open source.

What is cucumber in selenium? 
it is library wich is used to achieve Behaviour deriven testing.


How do you write an Xpath locator to identify paragraph elements that are the immediate child of a div element,

//div::child[//p]
