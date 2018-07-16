# JMeterForAPITesting
JMeterForAPITesting

Download: https://jmeter.apache.org/download_jmeter.cgi

## API Testing
API - Application Programming Interface

+ Request method: `GET, POST, PUT, DELETE`
HTTP protocol: `http, https`
+ Request Message
+ Response Message

API Response Code: 
 ```
  200: Request successfull
  400: Bad request or request was corupted
  401: Unthorization access 
  403: Forbiden access
  404: Request Resource does not exist.
  500: Internal Server error
  ```

API Types:
+ REST API
+ SOAP API 

## Basic JMeter

### 1. Make a sample request

We will add a Thread Group to a test plan on our JMeter script.
```
Test Plan >> Add >> Threads (Users) >> Thread Group
```
Addd a Simple Controller 
```
Thread Groud >> Add > Logic Controller >> Simple Controller
```
Add a sample http request
```
Thread Group >> Add >> Sampler >> HTTP Request
``` 
### 2. Create a test plan with a template

```
Menu: File > Templates > Select a Template >> [Done]
```

### 3. User Defined Variable

```

```

### 4. HTTP Request Defaults

```
Thread Group >> Add >> Config Element >> HTTP Request Defaults
Input: Webserver with Protocol and Server Name
```

### 5. HTTP Header Manager

```
Thread Group >> Add >> Config Element >> HTTP Header Manager
```

### 4. Popular Listener 

### 5. Popular JMeter Functions

ThreadNum
```
${__threadNum}
```
SamplerName
```
${__samplerName}
```
FunctionName
```
${__functionName}
```
Counter
```
${__counter(false,result)}
${result}
```
![](https://github.com/josdoaitran/JMeterForAPITesting/blob/master/Images/CounterJMeter.png)

Time Function
```
${__time}
${__time(YMD)}
${__time(YMDHM, result)}
${result}
```
UUID
```
Function >> Function Helper Dialog >> Choose a function: '__UUID'
${UUID()}
```

# Rest API Handling

- Authorization
- Post Request
- Put Request

# SOAP APIT Testing with JMeter

```

```
# Using CSV Data Config
- Create a csv file
- Add CSV Data config
```
Add >> Config Elements >> CSV Data Config
```

CSV file has contents like: 
```
sigupEmail, username
penapi1@mailinator.com, penapi1
penapi2@mailinator.com, penapi2
```
# Handling Assertions
```

```
# Realtime Scripts
```

```

# ANT Tools interactive reports - JTL File for custom reports


# References

http://jmeter.apache.org/usermanual/jmeter_proxy_step_by_step.pdf
