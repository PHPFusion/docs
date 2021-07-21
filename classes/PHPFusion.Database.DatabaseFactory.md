# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Database\DatabaseFactory
### Namespace: [\PHPFusion\Database](../namespaces/PHPFusion.Database.md)
---
---
### Constants
* [ DRIVER_MYSQLi](../classes/PHPFusion.Database.DatabaseFactory.md#constant_DRIVER_MYSQLi)
* [ DRIVER_PDO_MYSQL](../classes/PHPFusion.Database.DatabaseFactory.md#constant_DRIVER_PDO_MYSQL)
* [ DRIVER_DEFAULT](../classes/PHPFusion.Database.DatabaseFactory.md#constant_DRIVER_DEFAULT)
---
### Properties
* [private $defaultDriver](../classes/PHPFusion.Database.DatabaseFactory.md#property_defaultDriver)
* [private $debug](../classes/PHPFusion.Database.DatabaseFactory.md#property_debug)
* [private $driverClasses](../classes/PHPFusion.Database.DatabaseFactory.md#property_driverClasses)
* [private $configurations](../classes/PHPFusion.Database.DatabaseFactory.md#property_configurations)
* [private $defaultConnectionID](../classes/PHPFusion.Database.DatabaseFactory.md#property_defaultConnectionID)
* [private $connections](../classes/PHPFusion.Database.DatabaseFactory.md#property_connections)
---
### Methods
* [public registerDriverClass()](../classes/PHPFusion.Database.DatabaseFactory.md#method_registerDriverClass)
* [public registerConfigurationFromFile()](../classes/PHPFusion.Database.DatabaseFactory.md#method_registerConfigurationFromFile)
* [public registerConfigurations()](../classes/PHPFusion.Database.DatabaseFactory.md#method_registerConfigurations)
* [public registerConfiguration()](../classes/PHPFusion.Database.DatabaseFactory.md#method_registerConfiguration)
* [public isDebug()](../classes/PHPFusion.Database.DatabaseFactory.md#method_isDebug)
* [public setDebug()](../classes/PHPFusion.Database.DatabaseFactory.md#method_setDebug)
* [public getConnection()](../classes/PHPFusion.Database.DatabaseFactory.md#method_getConnection)
* [public getDefaultConnectionId()](../classes/PHPFusion.Database.DatabaseFactory.md#method_getDefaultConnectionId)
* [public connect()](../classes/PHPFusion.Database.DatabaseFactory.md#method_connect)
* [public getDriverClass()](../classes/PHPFusion.Database.DatabaseFactory.md#method_getDriverClass)
* [public getDefaultDriver()](../classes/PHPFusion.Database.DatabaseFactory.md#method_getDefaultDriver)
* [public setDefaultDriver()](../classes/PHPFusion.Database.DatabaseFactory.md#method_setDefaultDriver)
---
### Details
* File: [classes\PHPFusion\Database\DatabaseFactory.php](../files/classes.PHPFusion.Database.DatabaseFactory.md)
* Package: Default
* Class Hierarchy:
  * \PHPFusion\Database\DatabaseFactory
---
## Constants
<a name="constant_DRIVER_MYSQLi" class="anchor"></a>
###### DRIVER_MYSQLi*use mysqli_* functions*

```
DRIVER_MYSQLi = 'mysqli'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_DRIVER_PDO_MYSQL" class="anchor"></a>
###### DRIVER_PDO_MYSQL*use \PDO class*

```
DRIVER_PDO_MYSQL = 'pdo_mysql'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_DRIVER_DEFAULT" class="anchor"></a>
###### DRIVER_DEFAULT*Use the default driver (pdo_mysql)*

```
DRIVER_DEFAULT = self::DRIVER_PDO_MYSQL
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_defaultDriver"></a>
#### private $defaultDriver : string
---
**Summary**

MySQLi or PDOMySQL

**Type:** string

**Details:**


<a name="property_debug"></a>
#### private $debug : boolean|array
---
**Type:** boolean|array
Array of connection IDs or TRUE to debug all connections
**Details:**


<a name="property_driverClasses"></a>
#### private $driverClasses : array&lt;mixed,string&gt;
---
**Type:** array&lt;mixed,string&gt;

**Details:**


<a name="property_configurations"></a>
#### private $configurations : array&lt;mixed,\PHPFusion\Database\Configuration&gt;
---
**Type:** array&lt;mixed,<a href="../classes/PHPFusion.Database.Configuration.html">\PHPFusion\Database\Configuration</a>&gt;

**Details:**


<a name="property_defaultConnectionID"></a>
#### private $defaultConnectionID : string
---
**Type:** string

**Details:**


<a name="property_connections"></a>
#### private $connections : array&lt;mixed,\PHPFusion\Database\AbstractDatabaseDriver&gt;
---
**Type:** array&lt;mixed,<a href="../classes/PHPFusion.Database.AbstractDatabaseDriver.html">\PHPFusion\Database\AbstractDatabaseDriver</a>&gt;

**Details:**



---
## Methods
<a name="method_registerDriverClass" class="anchor"></a>
#### public registerDriverClass() 

```
Static public registerDriverClass(string  $id, string  $fullClassName) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  |  |
| <code>string</code> | $fullClassName  |  |




<a name="method_registerConfigurationFromFile" class="anchor"></a>
#### public registerConfigurationFromFile() 

```
Static public registerConfigurationFromFile(string  $file) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $file  |  |




<a name="method_registerConfigurations" class="anchor"></a>
#### public registerConfigurations() 

```
Static public registerConfigurations(array  $configurations) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $configurations  |  |




<a name="method_registerConfiguration" class="anchor"></a>
#### public registerConfiguration() 

```
Static public registerConfiguration(integer  $id, array  $configuration) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $id  |  |
| <code>array</code> | $configuration  |  |




<a name="method_isDebug" class="anchor"></a>
#### public isDebug() : boolean

```
Static public isDebug(string  $connectionid = NULL) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $connectionid  |  |

**Returns:** boolean


<a name="method_setDebug" class="anchor"></a>
#### public setDebug() 

```
Static public setDebug(boolean&amp;#124;array  $debug = TRUE) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean&#124;array</code> | $debug  |  |




<a name="method_getConnection" class="anchor"></a>
#### public getConnection() : \PHPFusion\Database\AbstractDatabaseDriver

```
Static public getConnection(string  $id = NULL) : \PHPFusion\Database\AbstractDatabaseDriver
```

**Summary**

Get the database connection object

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Database\Exception\UndefinedConfigurationException |  |

**Returns:** <a href="../classes/PHPFusion.Database.AbstractDatabaseDriver.html">\PHPFusion\Database\AbstractDatabaseDriver</a>


<a name="method_getDefaultConnectionId" class="anchor"></a>
#### public getDefaultConnectionId() : string

```
Static public getDefaultConnectionId() : string
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)

**Returns:** string


<a name="method_connect" class="anchor"></a>
#### public connect() : \PHPFusion\Database\AbstractDatabaseDriver

```
Static public connect(string  $host, string  $user, string  $password, string  $db, array  $options = array()) : \PHPFusion\Database\AbstractDatabaseDriver
```

**Summary**

Connect to the database using the default driver

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $host  |  |
| <code>string</code> | $user  |  |
| <code>string</code> | $password  |  |
| <code>string</code> | $db  |  |
| <code>array</code> | $options  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Database\Exception\SelectionException |  |
| \PHPFusion\Database\Exception\ConnectionException |  |

**Returns:** <a href="../classes/PHPFusion.Database.AbstractDatabaseDriver.html">\PHPFusion\Database\AbstractDatabaseDriver</a>


<a name="method_getDriverClass" class="anchor"></a>
#### public getDriverClass() : null&amp;#124;string

```
Static public getDriverClass(string  $id = NULL) : null&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  |  |

**Returns:** null&#124;string


<a name="method_getDefaultDriver" class="anchor"></a>
#### public getDefaultDriver() : string

```
Static public getDefaultDriver() : string
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)

**Returns:** string


<a name="method_setDefaultDriver" class="anchor"></a>
#### public setDefaultDriver() 

```
Static public setDefaultDriver(string  $defaultDriver) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\DatabaseFactory](../classes/PHPFusion.Database.DatabaseFactory.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $defaultDriver  |  |





---

### Top Namespaces

* [\Defender](../namespaces/Defender.html.md)
* [\PHPFusion](../namespaces/PHPFusion.html.md)

---

### Reports
* [Errors - 1023](../reports/errors.md)
* [Markers - 6](../reports/markers.md)
* [Deprecated - 36](../reports/deprecated.md)

---

This document was automatically generated from source code comments on 2021-07-21 using [phpDocumentor](http://www.phpdoc.org/) and [fr3nch13/phpdoc-markdown](https://github.com/fr3nch13/phpdoc-markdown)
