# Magentron\ApiLogger\Middleware\ApiLoggerMiddleware  







## Methods

| Name | Description |
|------|-------------|
|[__construct](#apiloggermiddleware__construct)|ApiLoggerMiddleware constructor.|
|[getFilename](#apiloggermiddlewaregetfilename)|Get filename to use for log file.|
|[getFilenamePostfix](#apiloggermiddlewaregetfilenamepostfix)|Retrieve log filename postfix based on rotation configuration.|
|[getLogData](#apiloggermiddlewaregetlogdata)|Get data to log for request.|
|[handle](#apiloggermiddlewarehandle)|Handle an incoming request.|
|[logRequest](#apiloggermiddlewarelogrequest)|Log request to file.|




### ApiLoggerMiddleware::__construct  

**Description**

```php
public __construct (void)
```

ApiLoggerMiddleware constructor. 

Loads configuration. 

**Parameters**

`This function has no parameters.`

**Return Values**

`void`


<hr />


### ApiLoggerMiddleware::getFilename  

**Description**

```php
public getFilename (int $time)
```

Get filename to use for log file. 

 

**Parameters**

* `(int) $time`

**Return Values**

`string`




<hr />


### ApiLoggerMiddleware::getFilenamePostfix  

**Description**

```php
public getFilenamePostfix (int $time)
```

Retrieve log filename postfix based on rotation configuration. 

 

**Parameters**

* `(int) $time`

**Return Values**

`bool|string`




<hr />


### ApiLoggerMiddleware::getLogData  

**Description**

```php
public getLogData (\Illuminate\Http\Request $request, \Symfony\Component\HttpFoundation\Response $response, array $microtime)
```

Get data to log for request. 

 

**Parameters**

* `(\Illuminate\Http\Request) $request`
* `(\Symfony\Component\HttpFoundation\Response) $response`
* `(array) $microtime`

**Return Values**

`array`




<hr />


### ApiLoggerMiddleware::handle  

**Description**

```php
public handle (\Illuminate\Http\Request $request, \Closure $next)
```

Handle an incoming request. 

 

**Parameters**

* `(\Illuminate\Http\Request) $request`
* `(\Closure) $next`

**Return Values**

`mixed`




<hr />


### ApiLoggerMiddleware::logRequest  

**Description**

```php
public logRequest (\Illuminate\Http\Request $request, \Symfony\Component\HttpFoundation\Response $response)
```

Log request to file. 

 

**Parameters**

* `(\Illuminate\Http\Request) $request`
* `(\Symfony\Component\HttpFoundation\Response) $response`

**Return Values**

`void`


<hr />

