# TESTING

Testing is the procedure of assessing a system or its individual components with the purpose of determining whether they meet the specified requirements. This evaluation activity involves comparing the actual results obtained during testing with the expected results to identify any disparities. By employing various techniques, such as functional, performance, and reliability testing, defects or errors in the system are discovered, enabling further investigation and debugging to address them.

Testing is a vital process in ensuring the quality and accuracy of a system, instilling confidence in its performance and dependabilit


Testing concepts

When to Start Testing

An early start to testing reduces the cost, time to rework and error free software that is delivered to the client. However in Software Development Life Cycle (SDLC) testing can be started from the Requirements Gathering phase and lasts till the deployment of the software.it depends on the development model that is being used

When to Stop Testing

It is difficult to determine when to stop testing, as testing is a never ending process and no one can say that any software is 100% tested.

Verification & Validation

Verification

1 Ensure that the software system meets all the functionality.
2 Verification takes place first and includes the checking for documentation, code etc.
3 Done by developers.

Validation
1 Ensure that functionalities meet the intended behavior.
2 Validation occurs after verification and mainly involves the checking of the overall product.
3 Done by Testers

Advantage of testing

 Functionality
 Reliability
 Usability
 Efficiency
 Maintainability
 Portability

Testing Types

1. Manual testing
2. Automation testing

Manual Testing

This type includes the testing of the Software manually without using any automated tool or any script.
In this type the tester takes over the role of an end user and test the Software to identify any un-expected behavior or bug.
Testers use test plan, test cases or test scenarios to test the Software to ensure the completeness of testing. Manual testing also includes exploratory testing as testers explore the software to identify errors in it.


Automation testing

Automation testing which is also known as “Test Automation”, is when the tester writes scripts and uses another software to test the software. This process involves automation of a manual process. 

Automation Testing is used to re-run the test scenarios that were performed manually, quickly and repeatedly. It is not possible to automate everything in the Software




SDLC

rq analysis
design
code
test
deploy

STLC

test planning
case development
environment setup
execution
bug reporting
retest
regression
test cycle closure


Testing Methods

<Blackbox><whitebox><graybox>

black box testing

user story
test data
test staragie
test case design
test case
test exceute
clouser

black box types
 
fuctional
non functional
regression


white box testing 
* unit testing

fuctional testing vs non functional testing

fuctional testing is to test the fuction of the application 
non f testing is to test the perfromance of the apllication

smoke test

smoke test are used to determine whether the build is stable enough to proceed with more thorough testing. if it is not other test not will considerable becasue it test the most ciritical fuctional first
The term "smoke test" comes from the concept of testing whether there is smoke coming out of a machine before turning it on. If there is smoke, it indicates a problem that needs to be fixed before the machine can be used.

this is subset of acceptance testing
 
other name :
Build Verification Testing (BVT):
Sanity testing:
bulid or tester Acceptance testing:
Quick testing:

sanity test 

smiliar to smoke but the differance is it test the new build or bug fixed build 
the work is to test the bug area is that fixed are not
then when its come to new build it need to test the  most neccessary need fuction of the new build

this is subset of regression testing.



regression testing

this is superset of sanity testing
when ever the new or bug fixed build comes first need to test that particular area when its works properly then we need to test all components in that same area

Regression testing is a type of software testing that verifies whether changes or modifications to an application have introduced new defects or affected existing functionalities.
It involves re-executing previously executed test cases to ensure that the changes have not caused any unintended consequences. 
The main objective of regression testing is to ensure that the quality and stability of the software are not compromised during the development process.


retesting

test riase a bug in certain test case and after dev team fixed it then we test the same case is known as retesting


adhoc testing 

adhoc means done without any planned or oragainsed or without reherased is known as aadhoc 
adhoc testing doesn't any type of documented process to be followed
 
types of adhoc testing

buddy - dev + tester
pair - more than 2 tester
monkey - need to break the product with any way


defect vs bug 
simply it deviation between of the actual and expected behaviour of the application 

in jiira it is bug
in qtp or hp it is defect

atlast everthing is an issues to cleared


bug life cycle

severity vs piority 

in the most of case these two are directely proprotional to each other

high severity high poriorty



severity is measure of impact of the bug or defect in software product

types

low
minior
major
ciritical

piority

it refers a which bug need to be fixed first

types

low
medium
high


Test secnario 

The high level one line of the test cases is known as test secnarios

Test case

Test cases involve the set of steps, conditions and inputs which can be used while
performing the testing tas








