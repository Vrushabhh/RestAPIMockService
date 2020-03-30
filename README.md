# RestAPIMockService
1) Install SOAP-UI - https://www.soapui.org/downloads/soapui.html - Open Source
2) Extract .zip file
3) After installing SOAP-UI tool
4) File -> Import Project -> local extract .xml file
5) Expand project then Right Click on ValidateMockService -> Show Rest MockService Editor
6) Click on Play button (Green)
7) Point/Replace Rest URL - http://localhost:8080/api/v3/validate in Automation Suite or any rest client
8) Run the test

#Execute Mock Service Command-Line
1) Extract .zip file
2) Place unzipped .xml file under bin folder of SOAP-UI installation path . Ex - C:\Program Files\SmartBear\SoapUI-5.4.0\bin
3) open command promt in same path and execute this command --> executemockservicerunner <FileName.xml> Ex - mockservicerunner MockTest.xml
