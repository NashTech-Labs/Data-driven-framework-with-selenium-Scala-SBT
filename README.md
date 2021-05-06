# Data-driven-framework-with-selenium-Scala-SBT

### Introduction:-
This repository contains a plug and play template of a data driven framework using selenium and Scala. This template uses data 
from an Excel sheet and uses it in tests.

### Why do we need Data driven framework?

Data Driven framework helps us in separating the test scripts logic and the test data from one another. 
It allows us to write test automation scripts in which we can pass different sets of test data.
The main reason behind a data-driven framework is re-usability of code. 
The same block of code can be reused multiple times with different data set every time.

### Technologies used:-
**Programming language** - Scala

**Build tool** - SBT

**Automation tool** - Selenium

**IDE** - Intellij

###Dependencies used :
**Apache POI**

`"org.apache.poi" % "poi" % "5.0.0"`

`"org.apache.poi" % "poi-ooxml" % "5.0.0"`

`"org.apache.poi" % "poi" % "5.0.0"`

**Selenium scala test**

`"org.scalatestplus" %% "selenium-3-141" % "3.2.2.0" % "test"`


**Scala test**

`"org.scalatest" %% "scalatest-flatspec" % "3.2.2" % "test"`

`"org.scalatest" %% "scalatest-shouldmatchers" % "3.2.2" % "test"`

`"org.scalatest" %% "scalatest-funsuite" % "3.2.2" % "test"`


### Steps for execution:-
Clone the repository on your local system.

Let intellij resolve all the required dependencies.

Add the latest chromedriver or firefox driver (gecko driver) into the DriverFiles folder.

Place the required Excel (.xlsx) file in the Data folder.

Go to the terminal the and execute the command **sbt test** to execute all the tests.