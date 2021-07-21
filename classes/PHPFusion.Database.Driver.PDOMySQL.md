# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Database\Driver\PDOMySQL
### Namespace: [\PHPFusion\Database\Driver](../namespaces/PHPFusion.Database.Driver.md)
---
**Summary:**

Abstract class for new database handler classes

---
### Constants
* [ ERROR_UNKNOWN_DATABASE](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#constant_ERROR_UNKNOWN_DATABASE)
* [ PARAM_NULL](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#constant_PARAM_NULL)
* [ PARAM_INT](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#constant_PARAM_INT)
* [ PARAM_STR](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#constant_PARAM_STR)
* [ PARAM_BOOL](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#constant_PARAM_BOOL)
---
### Properties
* [private $queries](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#property_queries)
* [private $debug](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#property_debug)
* [private $connectionid](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#property_connectionid)
* [private $paramTypeMap](../classes/PHPFusion.Database.Driver.PDOMySQL.md#property_paramTypeMap)
* [private $connection](../classes/PHPFusion.Database.Driver.PDOMySQL.md#property_connection)
---
### Methods
* [public __construct()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method___construct)
* [public getGlobalQueryCount()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getGlobalQueryCount)
* [public getGlobalQueryLog()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getGlobalQueryLog)
* [public getGlobalQueryTimeSum()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getGlobalQueryTimeSum)
* [public getParameterType()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getParameterType)
* [public close()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_close)
* [public isClosed()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_isClosed)
* [public isConnected()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_isConnected)
* [public isDebug()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_isDebug)
* [public setDebug()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_setDebug)
* [public getQueryLog()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getQueryLog)
* [public getQueryCount()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getQueryCount)
* [public getQueryTimeSum()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getQueryTimeSum)
* [public fetchAllAssoc()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_fetchAllAssoc)
* [public fetchAssoc()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_fetchAssoc)
* [public fetchAllRows()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_fetchAllRows)
* [public fetchRow()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_fetchRow)
* [public getNextId()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_getNextId)
* [public query()](../classes/PHPFusion.Database.AbstractDatabaseDriver.md#method_query)
* [public _query()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method__query)
* [public count()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_count)
* [public fetchFirstColumn()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_fetchFirstColumn)
* [public countRows()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_countRows)
* [public countColumns()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_countColumns)
* [public getLastId()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_getLastId)
* [public quote()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_quote)
* [public getServerVersion()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_getServerVersion)
* [protected connect()](../classes/PHPFusion.Database.Driver.PDOMySQL.md#method_connect)
---
### Details
* File: [classes\PHPFusion\Database\Driver\PDOMySQL.php](../files/classes.PHPFusion.Database.Driver.PDOMySQL.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
  * \PHPFusion\Database\Driver\PDOMySQL
---
## Constants
<a name="constant_ERROR_UNKNOWN_DATABASE" class="anchor"></a>
###### ERROR_UNKNOWN_DATABASEInherited from [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
*This is a MySQL error code*

```
ERROR_UNKNOWN_DATABASE = 1049
```

http://dev.mysql.com/doc/refman/5.5/en/error-messages-server.html
| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PARAM_NULL" class="anchor"></a>
###### PARAM_NULLInherited from [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

```
PARAM_NULL = 'null'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PARAM_INT" class="anchor"></a>
###### PARAM_INTInherited from [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

```
PARAM_INT = 'int'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PARAM_STR" class="anchor"></a>
###### PARAM_STRInherited from [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

```
PARAM_STR = 'string'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_PARAM_BOOL" class="anchor"></a>
###### PARAM_BOOLInherited from [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

```
PARAM_BOOL = 'bool'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_queries"></a>
#### private $queries : array
---
**Summary**

It stores the SQL queries and execution times sent by every instance

**Type:** array

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)


<a name="property_debug"></a>
#### private $debug : boolean
---
**Type:** boolean

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)


<a name="property_connectionid"></a>
#### private $connectionid : string
---
**Type:** string

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)


<a name="property_paramTypeMap"></a>
#### private $paramTypeMap : 
---
**Type:** 

**Details:**


<a name="property_connection"></a>
#### private $connection : \PDO
---
**Type:** \PDO

**Details:**



---
## Methods
<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct(string  $host, string  $user, string  $pass, string  $db, array  $options = array()) 
```

**Summary**

Connect to the database

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $host  | Server domain or IP followed by an optional port definition |
| <code>string</code> | $user  |  |
| <code>string</code> | $pass  | Password |
| <code>string</code> | $db  | The name of the database |
| <code>array</code> | $options  | Currently only one option exists: charset |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPFusion\Database\Exception\SelectionException | When the selection of the database was unsuccessful |
| \PHPFusion\Database\Exception\ConnectionException | When the connection could not be established |




<a name="method_getGlobalQueryCount" class="anchor"></a>
#### public getGlobalQueryCount() : integer

```
Static public getGlobalQueryCount() : integer
```

**Summary**

Get the number of queries of all connections

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** integer


<a name="method_getGlobalQueryLog" class="anchor"></a>
#### public getGlobalQueryLog() : array

```
Static public getGlobalQueryLog() : array
```

**Summary**

Get all queries of all connections

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** array - structure: array(
       $connectionid => array(
           array($time, $sql, $parameters),
           //...
       ),
       //...
)


<a name="method_getGlobalQueryTimeSum" class="anchor"></a>
#### public getGlobalQueryTimeSum() : float

```
Static public getGlobalQueryTimeSum() : float
```

**Summary**

Get the summarized execution time of all queries of all connections

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** float


<a name="method_getParameterType" class="anchor"></a>
#### public getParameterType() : string

```
Static public getParameterType(string  $parameter) : string
```

**Summary**

Returns the type of the given parameter

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $parameter  |  |

**Returns:** string - Possible values:
   <ul>
       <li>{@link AbstractDatabaseDriver::PARAM_INT}</li>
       <li>{@link AbstractDatabaseDriver::PARAM_STR}</li>
       <li>{@link AbstractDatabaseDriver::PARAM_BOOL}</li>
       <li>{@link AbstractDatabaseDriver::PARAM_NULL}</li>
   </ul>


<a name="method_close" class="anchor"></a>
#### public close() 

```
public close() 
```

**Summary**

Close the connection

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)




<a name="method_isClosed" class="anchor"></a>
#### public isClosed() : boolean

```
public isClosed() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** boolean - TRUE if the connection is closed


<a name="method_isConnected" class="anchor"></a>
#### public isConnected() : boolean

```
public isConnected() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)

**Returns:** boolean - TRUE if the connection is alive


<a name="method_isDebug" class="anchor"></a>
#### public isDebug() : boolean

```
public isDebug() : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** boolean


<a name="method_setDebug" class="anchor"></a>
#### public setDebug() 

```
public setDebug(boolean  $debug = TRUE) 
```

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $debug  |  |




<a name="method_getQueryLog" class="anchor"></a>
#### public getQueryLog() : array

```
public getQueryLog() : array
```

**Summary**

Get all queries of this connection

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** array - structure: array(
       $connection_hash => array(
           array($time, $sql),
           //...
       ),
       //...
)


<a name="method_getQueryCount" class="anchor"></a>
#### public getQueryCount() : integer

```
public getQueryCount() : integer
```

**Summary**

Get the number of queries of this connection

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** integer


<a name="method_getQueryTimeSum" class="anchor"></a>
#### public getQueryTimeSum() : float

```
public getQueryTimeSum() : float
```

**Summary**

Get the summarized execution time of all queries of this connection

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)

**Returns:** float


<a name="method_fetchAllAssoc" class="anchor"></a>
#### public fetchAllAssoc() : array

```
public fetchAllAssoc(mixed  $result) : array
```

**Summary**

Fetch all rows as associative arrays

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array


<a name="method_fetchAssoc" class="anchor"></a>
#### public fetchAssoc() : array

```
public fetchAssoc(\PDOStatement  $result) : array
```

**Summary**

Fetch one row as an associative array

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>\PDOStatement</code> | $result  | The result of a query |

**Returns:** array - Associative array


<a name="method_fetchAllRows" class="anchor"></a>
#### public fetchAllRows() : array

```
public fetchAllRows(mixed  $result) : array
```

**Summary**

Fetch all rows as numeric arrays

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array


<a name="method_fetchRow" class="anchor"></a>
#### public fetchRow() : array

```
public fetchRow(\PDOStatement  $result) : array
```

**Summary**

Fetch one row as a numeric array

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>\PDOStatement</code> | $result  | The result of a query |

**Returns:** array - Numeric array


<a name="method_getNextId" class="anchor"></a>
#### public getNextId() : integer&amp;#124;false

```
public getNextId(string  $table) : integer&amp;#124;false
```

**Summary**

Get the next auto_increment id of a table

**Description**

Try to avoid the use of it! \getLastId() after insert
is more secure way to get the id of an existing record than
get just a potential id.

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table  |  |

**Returns:** integer&#124;false


<a name="method_query" class="anchor"></a>
#### public query() : mixed

```
public query(string  $query, array  $parameters = array()) : mixed
```

**Summary**

Send a database query

**Details:**
* Inherited From: [\PHPFusion\Database\AbstractDatabaseDriver](../classes/PHPFusion.Database.AbstractDatabaseDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $query  | SQL |
| <code>array</code> | $parameters  |  |

**Returns:** mixed - The result of the query or FALSE on error


<a name="method__query" class="anchor"></a>
#### public _query() : \PDOStatement&amp;#124;boolean

```
public _query(string  $query, array  $parameters = array()) : \PDOStatement&amp;#124;boolean
```

**Summary**

Send a database query

**Description**

This method will be called from AbstractDatabase::query()
AbstractDatabase::query() will log the queries and check the
execution time.

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $query  | SQL |
| <code>array</code> | $parameters  |  |

**Returns:** \PDOStatement&#124;boolean - on error


<a name="method_count" class="anchor"></a>
#### public count() : integer

```
public count(string  $field, string  $table, string  $conditions = &quot;&quot;, array  $parameters = array()) : integer
```

**Summary**

Count the number of rows in a table filtered by conditions

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  | Parenthesized field name |
| <code>string</code> | $table  | Table name |
| <code>string</code> | $conditions  | conditions after "where" |
| <code>array</code> | $parameters  |  |

**Returns:** integer


<a name="method_fetchFirstColumn" class="anchor"></a>
#### public fetchFirstColumn() : mixed

```
public fetchFirstColumn(\PDOStatement  $result, integer  $row) : mixed
```

**Summary**

Fetch the first column of a specific row

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>\PDOStatement</code> | $result  | The result of a query |
| <code>integer</code> | $row  |  |

**Returns:** mixed


<a name="method_countRows" class="anchor"></a>
#### public countRows() : integer

```
public countRows(\PDOStatement  $result) : integer
```

**Summary**

Count the number of affected rows by the given query

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>\PDOStatement</code> | $result  | The result of a query |

**Returns:** integer


<a name="method_countColumns" class="anchor"></a>
#### public countColumns() : integer

```
public countColumns(\PDOStatement  $result) : integer
```

**Summary**

Count the number of affected columns by the given query

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>\PDOStatement</code> | $result  | The result of a query |

**Returns:** integer


<a name="method_getLastId" class="anchor"></a>
#### public getLastId() : integer

```
public getLastId() : integer
```

**Summary**

Get the last inserted auto increment id

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)

**Returns:** integer


<a name="method_quote" class="anchor"></a>
#### public quote() : string

```
public quote(string  $value) : string
```

**Summary**

Implementation of \PDO::quote()

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
* See Also:
 * [http://php.net/manual/en/pdo.quote.php](http://php.net/manual/en/pdo.quote.php)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |

**Returns:** string


<a name="method_getServerVersion" class="anchor"></a>
#### public getServerVersion() : string

```
public getServerVersion() : string
```

**Summary**

Get the database server version

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)

**Returns:** string


<a name="method_connect" class="anchor"></a>
#### protected connect() 

```
protected connect(string  $host, string  $user, string  $pass, string  $db, array  $options = array()) 
```

**Summary**

Connect to the database

**Details:**
* Inherited From: [\PHPFusion\Database\Driver\PDOMySQL](../classes/PHPFusion.Database.Driver.PDOMySQL.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $host  | Server domain or IP followed by an optional port definition |
| <code>string</code> | $user  |  |
| <code>string</code> | $pass  | Password |
| <code>string</code> | $db  | The name of the database |
| <code>array</code> | $options  | Currently only one option exists: charset |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \ErrorException | When the connection could not be established |





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
