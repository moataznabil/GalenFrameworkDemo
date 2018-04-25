# GalenFrameworkDemo

This Repository for my LinkedIn Article about how to use Galen Framework in Layout and Responsive testing
https://www.linkedin.com/pulse/automated-layout-testing-using-galen-framework-moataz-nabil/


[![Build Status](https://travis-ci.org/moataznabil/GalenFrameworkDemo.svg?branch=master)](https://travis-ci.org/moataznabil/GalenFrameworkDemo)

# How to use it

1- Install Galen

```sh
npm install -g galenframework-cli
```
2- check Galen is installed successfully
```sh
galen -v
```

3- Clone the Repository 
 
```sh
git clone https://github.com/moataznabil/GalenFrameworkDemo.git

```

4- Goto the Project folder
```sh
cd GalenFrameworkDemo
```

5- run the galen test command 
```sh
galen test tests/homepage.test.js --htmlreport reports
```

6- You will find the reports folder created and you can check the report by open "Report.html"

