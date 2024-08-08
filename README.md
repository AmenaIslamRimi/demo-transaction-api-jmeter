# Demo-Transaction-API-jmeter
# Objectives
D-money website is an e-commerce site. This tests was to ensure that the Transaction API performs correctly under various conditions without applying any load. The tests focused on verifying the functionality, error handling, and correctness of the API responses. 
# Prerequisites
* JDK (Latest LTS)
* Set environment for java JAVA-HOME
* Jmeter
* Set environment for JMeter JMETER-HOME
# How to run
## Execute following commands
* git clone <repo_url>
* ./jmeter (For Linux)
* or, .jmeter (For Windows)
# How to generate the report
## For JMeter 5.1.1 version or higher
To generate the report in Non-GUI mode, execute the test using the below command:
* For Windows: jmeter -n -t yourFile.jmx -l yourFile.csv -e -o Reports
* For Linux: ./jmeter.sh -n -t yourFile.jmx -l yourFile.csv -e -o Reports
### Generate a report with JMeter
* Thread groups > add > listener > Aggregate report
* In Aggregate report: Create filename 'filename.csv'
* (Top navbar) Tools > Generate HTML report > browse 'filename.csv' > browse 'user.properties' > give (empty folder) output directory
* Click Generate report
For both options, the output folder contains the generated report in HTML format at the end of the test.
# Tests Conducted
## API Test
The API Test was conducted to validate the functionality of the Transaction API, focusing on a series of transactions involving an admin, system, agent, customer, and merchant.
# Results 
## Screenshots
### API JMeter 
![api jmeter report](https://i.postimg.cc/Y9q6jy49/api-jmeter-report.png) 
