# Testsper

First [install CasperJS](http://docs.casperjs.org/en/latest/installation.html)

```shell
npm install -g phantomjs
npm install -g casperjs

casperjs test googletesting.js --xunit=googletestingresult.xml
```

This is a simple integration test, the results are exported as JUnit XML (xUnit) that will be easly parsed by the Jenkins Job Runner

>**Read the [full documentation](http://docs.casperjs.org/) on casperjs documentation website.**
>