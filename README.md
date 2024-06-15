# WebEXPRTool
## Why another version of the same tool?
This is the migration of the Python based EXPR tool to a web based tool.  
I see the following as shortcomings of the python based tool
1. Needs python compiler to run the code - which is not installed be default in all EWS's 
2. Python uses dependencies like Pandas (library dependency) - this may break during upgrades. Makes is the overall solution difficult to maintain
3. If the tool were to be passed on to another user, the setting up of python ecosystem is time consuming

In order to overcome the above, it is justified to create a web based tool that can run on any machine.

## Leverage
This tool will leverage the existing python code for the concat constructs required to develop the automation node instances

## Known issues
Nothing yet
