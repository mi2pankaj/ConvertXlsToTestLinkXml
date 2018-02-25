# ConvertXlsToTestLinkXml
This code converts the xls (only) file into testlink compatible xml file, using this - test cases can be exported to testlink easily. 
Please use ONLY xls file having same format as described in SampleTestCase/SampleTestCase.xls.
To use this code, just change the values of variables in ConvertXlsToTestLinkXml.java file. Thats it.

String testcaseFile = System.getProperty("user.dir").concat("/SampleTestCase/SampleTestCase.xls");
String desiredTestlinkXMLFile = System.getProperty("user.dir").concat("/OutputTestLinkXmlFile/OutputTestLinkXmlFile.xml");

Only one dependency is reuquired - jxl jar. which is already added in lib folder and in pom.xml also. 
Just clone this repo and use it. 

In case something doesn't work, please raise issue or email me at mi2.pankaj@gmail.com and I'll get back to you asap.
Happy to help.

