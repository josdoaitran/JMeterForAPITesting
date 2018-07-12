# JMeterForAPITesting
JMeterForAPITesting

Download: https://jmeter.apache.org/download_jmeter.cgi

## API Testing

API Types:
+ REST API
+ SOAP API 
Request method: GET, POST, PUT, DELETE

## Basic JMeter

* Make a sample request

We will add a Thread Group to a test plan on our JMeter script.
```
Test Plan >> Add >> Threads (Users) >> Thread Group
```
Add a sample http request
```
Thread Group >> Add >> Sampler >> HTTP Request
```

* HTTP Request Defaults

```
Thread Group >> Add >> Config Element >> HTTP Request Defaults
Input: Webserver with Protocol and Server Name
```

http://jmeter.apache.org/usermanual/jmeter_proxy_step_by_step.pdf
