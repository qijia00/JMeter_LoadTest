# JMeter_LoadTest
Sample scripts that I created with JMeter for load testing.

# How to use this repo please read
README.docx

# How to execute script in cmd and create html dashboard report
create empty csv "empty.csv" in "results" folder, create empty folder "emptyFolder" in "reports" folder.
Don't use powershell, use cmd instead, nevigate to jmeter bin folder (no space allowed in path):
C:\apache-jmeter-5.1.1\apache-jmeter-5.1.1\bin>jmeter -n  -t C:\GitHub\JMeter\scripts\DemoTestPlan.jmx -l C:\GitHub\JMeter\results\empty.csv -e -o C:\GitHub\JMeter\reports\emptyFolder
