# JMeterForAPITesting
JMeterForAPITesting

Download: https://jmeter.apache.org/download_jmeter.cgi

## API Testing

API Types:
+ REST API
+ SOAP API 
Request method: GET, POST, PUT, DELETE

## Basic JMeter

### 1. Make a sample request

We will add a Thread Group to a test plan on our JMeter script.
```
Test Plan >> Add >> Threads (Users) >> Thread Group
```
Add a sample http request
```
Thread Group >> Add >> Sampler >> HTTP Request
```

### 2. HTTP Request Defaults

```
Thread Group >> Add >> Config Element >> HTTP Request Defaults
Input: Webserver with Protocol and Server Name
```

### 3. HTTP Header Manager

```
Thread Group >> Add >> Config Element >> HTTP Header Manager
```

### 4. Popular Listener 

# Rest API Handling

- Authorization
- Post Request
- Put Request

# SOAP APIT Testing with JMeter

```

```
# Using CSV Data Config

```

```
# Handling Assertions
```

```
# Realtime Scripts
```

```

# References

http://jmeter.apache.org/usermanual/jmeter_proxy_step_by_step.pdf
