# DateCalculation
DateCalculation
Environment:

JAVA 6.0
Struts 1.3.10
Spring 3.2.4
JUNIT 4.0
Apache Tomcat 6.0
JAVAScript

SCOPE:
1) Input: String in Date Format 
	DD   MM  YYYY,  DD  MM  YYYY
2)Validations:  
	a) Validate String
		1. String Should be in valid Format(DD MM YYYY, DD MM YYYY)
		2. DD should be between 1-31
		3. MM should be between 1-12
		4. YYYY should be between 1999-2020
		5. leap years should match days in month(2)
	b) First Date should be earliest than Second Date
3) Business:
	a) Service to get Number of days between two dates
4)OutPut Format:
        DD  MM  YYYY, DD  MM  YYYY, DIFF_IN_DAYS
5)Test Cases:
      CORE JAVA JUNIT

Classes:
1) index.jsp
2) success.jsp
3) AppConstants.properties
4) UserInputDateFormBean.java
5) UserInputDateFormAction.java
6) DateCalculationUtil.java
7) DateCalculationFormService.java         [Interface]
8) DateCalculationFormServiceImpl.java
9) spring.xml
10) struts-config.xml



	
	

