# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Rewrite\Router
### Namespace: [\PHPFusion\Rewrite](../namespaces/PHPFusion.Rewrite.md)
---
**Summary:**

Rewrite API for PHPFusion
This Rewrite API handles the Permalinks Requests
and map them to suitable existing URLs in website.

**Description:**

You can use this API to Add custom rules for handling requests

---
### Constants
* No constants found
---
### Properties
* [public $routing](../classes/PHPFusion.Rewrite.Router.md#property_routing)
* [protected $data_statements](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_data_statements)
* [protected $handlers](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_handlers)
* [protected $queries](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_queries)
* [protected $output](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_output)
* [protected $rewrite_code](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_rewrite_code)
* [protected $rewrite_replace](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_rewrite_replace)
* [protected $pattern_tables](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_pattern_tables)
* [protected $alias_pattern](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_alias_pattern)
* [protected $pattern_search](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_pattern_search)
* [protected $pattern_replace](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_pattern_replace)
* [protected $patterns_regex](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_patterns_regex)
* [protected $aliases](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_aliases)
* [protected $regex_statements](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_regex_statements)
* [protected $requesturi](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_requesturi)
* [protected $warnings](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_warnings)
* [protected $buffer_search_regex](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_buffer_search_regex)
* [protected $path_search_regex](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_path_search_regex)
* [protected $dbid](../classes/PHPFusion.Rewrite.RewriteDriver.md#property_dbid)
* [private $router_instance](../classes/PHPFusion.Rewrite.Router.md#property_router_instance)
* [private $file_path](../classes/PHPFusion.Rewrite.Router.md#property_file_path)
* [private $get_parameters](../classes/PHPFusion.Rewrite.Router.md#property_get_parameters)
---
### Methods
* [public normalize()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_normalize) - (deprecated)
* [public __construct()](../classes/PHPFusion.Rewrite.Router.md#method___construct)
* [public removeParam()](../classes/PHPFusion.Rewrite.Router.md#method_removeParam)
* [public getRouterInstance()](../classes/PHPFusion.Rewrite.Router.md#method_getRouterInstance)
* [public getFileParams()](../classes/PHPFusion.Rewrite.Router.md#method_getFileParams)
* [public setPathtofile()](../classes/PHPFusion.Rewrite.Router.md#method_setPathtofile)
* [public setGetParameters()](../classes/PHPFusion.Rewrite.Router.md#method_setGetParameters)
* [public rewritePage()](../classes/PHPFusion.Rewrite.Router.md#method_rewritePage)
* [public setServerVars()](../classes/PHPFusion.Rewrite.Router.md#method_setServerVars)
* [public setQueryString()](../classes/PHPFusion.Rewrite.Router.md#method_setQueryString)
* [public getFilePath()](../classes/PHPFusion.Rewrite.Router.md#method_getFilePath)
* [public getCurrentURL()](../classes/PHPFusion.Rewrite.Router.md#method_getCurrentURL)
* [public get_FileParams()](../classes/PHPFusion.Rewrite.Router.md#method_get_FileParams) - (deprecated)
* [protected loadSqlDrivers()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_loadSqlDrivers)
* [protected includeRewrite()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_includeRewrite)
* [protected addRegexTag()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_addRegexTag)
* [protected verifyHandlers()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_verifyHandlers)
* [protected prepareSearchRegex()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_prepareSearchRegex)
* [protected appendSearchPath()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_appendSearchPath)
* [protected cleanRegex()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_cleanRegex)
* [protected handlePermalinkRequests()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_handlePermalinkRequests)
* [protected wrapQuotes()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_wrapQuotes)
* [protected wrapDoubleQuotes()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_wrapDoubleQuotes)
* [protected cleanUrl()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_cleanUrl)
* [protected handleNonSeoUrl()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_handleNonSeoUrl)
* [protected redirect301()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_redirect301)
* [protected replaceOtherTags()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_replaceOtherTags)
* [protected getTagPosition()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_getTagPosition)
* [protected setWarning()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_setWarning)
* [protected getUniqueIDtag()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_getUniqueIDtag)
* [protected makeSearchRegex()](../classes/PHPFusion.Rewrite.Router.md#method_makeSearchRegex)
* [protected setOutput()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_setOutput)
* [protected cleanString()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_cleanString)
* [private addRewrite()](../classes/PHPFusion.Rewrite.RewriteDriver.md#method_addRewrite)
* [private importPatterns()](../classes/PHPFusion.Rewrite.Router.md#method_importPatterns)
* [private checkAlias()](../classes/PHPFusion.Rewrite.Router.md#method_checkAlias)
* [private getAliasUrl()](../classes/PHPFusion.Rewrite.Router.md#method_getAliasUrl)
* [private explodeUrl()](../classes/PHPFusion.Rewrite.Router.md#method_explodeUrl)
* [private setVariables()](../classes/PHPFusion.Rewrite.Router.md#method_setVariables)
* [private buildParams()](../classes/PHPFusion.Rewrite.Router.md#method_buildParams)
* [private checkAliasPatterns()](../classes/PHPFusion.Rewrite.Router.md#method_checkAliasPatterns)
* [private checkPattern()](../classes/PHPFusion.Rewrite.Router.md#method_checkPattern)
* [private displayWarnings()](../classes/PHPFusion.Rewrite.Router.md#method_displayWarnings)
---
### Details
* File: [classes\PHPFusion\Rewrite\Router.php](../files/classes.PHPFusion.Rewrite.Router.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
  * \PHPFusion\Rewrite\Router
---
## Properties
<a name="property_routing"></a>
#### public $routing : boolean
---
**Summary**

True = SEF URL to FilePath
False = File Path to SEF URL

**Type:** boolean

**Details:**


<a name="property_data_statements"></a>
#### protected $data_statements : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_handlers"></a>
#### protected $handlers : 
---
**Summary**

Array of Handlers
example: news, threads, articles

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_queries"></a>
#### protected $queries : 
---
**Summary**

Array of Total Queries which were run.

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_output"></a>
#### protected $output : 
---
**Summary**

The site render HTML buffer which is to be scanned

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | string |

<a name="property_rewrite_code"></a>
#### protected $rewrite_code : 
---
**Summary**

Tags for the permalinks.

***Description***

example: %thread_id%, %news_id%

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_rewrite_replace"></a>
#### protected $rewrite_replace : 
---
**Summary**

Replacement for Tags for REGEX.

***Description***

example: %thread_id% should be replaced with ([0-9]+)

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_pattern_tables"></a>
#### protected $pattern_tables : 
---
**Summary**

Array of DB Table Names with Schema
example: prefix_news, prefix_threads, prefix_articles

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_alias_pattern"></a>
#### protected $alias_pattern : 
---
**Summary**

Array of Pattern for Aliases
which are made for matching.

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_pattern_search"></a>
#### protected $pattern_search : 
---
**Summary**

Permalink Patterns which will be searched
to match against current request.

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_pattern_replace"></a>
#### protected $pattern_replace : 
---
**Summary**

Target URLs to which permalink request
will be rewrited.

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_patterns_regex"></a>
#### protected $patterns_regex : 
---
**Summary**

Array of Regular Expressions Patterns
which are made for matching.

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_aliases"></a>
#### protected $aliases : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_regex_statements"></a>
#### protected $regex_statements : array
---
**Summary**

Statements are calculation results of Rewrite scan
We will have various types of regex statements
This is the results data of the entire permalink success/fails

**Type:** array

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_requesturi"></a>
#### protected $requesturi : 
---
**Summary**

Portion of the URL to match in the Regex

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | String |

<a name="property_warnings"></a>
#### protected $warnings : 
---
**Summary**

Array of Warnings

**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |

<a name="property_buffer_search_regex"></a>
#### protected $buffer_search_regex : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_path_search_regex"></a>
#### protected $path_search_regex : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_dbid"></a>
#### protected $dbid : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)


<a name="property_router_instance"></a>
#### private $router_instance : 
---
**Type:** 

**Details:**


<a name="property_file_path"></a>
#### private $file_path : 
---
**Summary**

Name of the php file which will be loaded
for the permalink.

***Description***

example: news.php, articles.php

**Type:** 

**Details:**

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | String |

<a name="property_get_parameters"></a>
#### private $get_parameters : 
---
**Summary**

Array of Parameters with their
actual values.

***Description***

example: thread_id => 1, rowstart => 20

**Type:** 

**Details:**

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| data_type |  | Array |


---
## Methods
<a name="method_normalize" class="anchor"></a>
#### (deprecated) - public normalize() : string

```
Static public normalize(  $string) : string
```

**Deprecated**
Deprecated
**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $string  |  |

**Returns:** string


<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_removeParam" class="anchor"></a>
#### public removeParam() : mixed&amp;#124;string

```
public removeParam(string  $url) : mixed&amp;#124;string
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  |  |

**Returns:** mixed&#124;string


<a name="method_getRouterInstance" class="anchor"></a>
#### public getRouterInstance() : static&amp;#124;null

```
Static public getRouterInstance() : static&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)

**Returns:** static&#124;null


<a name="method_getFileParams" class="anchor"></a>
#### public getFileParams() : array

```
public getFileParams() : array
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)

**Returns:** array


<a name="method_setPathtofile" class="anchor"></a>
#### public setPathtofile() 

```
public setPathtofile(mixed  $file_path) 
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $file_path  |  |




<a name="method_setGetParameters" class="anchor"></a>
#### public setGetParameters() 

```
public setGetParameters(mixed  $get_parameters) 
```

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $get_parameters  |  |




<a name="method_rewritePage" class="anchor"></a>
#### public rewritePage() 

```
public rewritePage() 
```

**Summary**

Call all the functions to process rewrite detection and further actions.

**Description**

This will call all the other functions after all the included files have been included
and all the patterns have been made.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_setServerVars" class="anchor"></a>
#### public setServerVars() 

```
public setServerVars() 
```

**Summary**

Set the PHP_SELF and SCRIPT_NAME to the suitable filepath.

**Description**

This function will set the values of PHP_SELF and SCRIPT_NAME to the suitable
file name. The filename will be searched in the $pattern_replace array.
The php filename is found before '?' in the pattern.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_setQueryString" class="anchor"></a>
#### public setQueryString() 

```
public setQueryString() 
```

**Summary**

Set the new QUERY_STRING
This function will set the values of QUERY_STRING to new value
which is calculated in buildParams().

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_getFilePath" class="anchor"></a>
#### public getFilePath() 

```
public getFilePath() 
```

**Summary**

Index Include File
Returns the filename of the php file which will be included.

**Description**

If this file is blank, index.php will redirect to 404 error page

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_getCurrentURL" class="anchor"></a>
#### public getCurrentURL() : string

```
public getCurrentURL() : string
```

**Summary**

Get the Current URL

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)

**Returns:** string


<a name="method_get_FileParams" class="anchor"></a>
#### (deprecated) - public get_FileParams() : array

```
public get_FileParams() : array
```

**Deprecated**
Deprecateduse getFileParams()
**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)

**Returns:** array


<a name="method_loadSqlDrivers" class="anchor"></a>
#### protected loadSqlDrivers() 

```
protected loadSqlDrivers() 
```

**Summary**

Import Handlers from Database
This will import all the Enabled Handlers from the Database Table

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_includeRewrite" class="anchor"></a>
#### protected includeRewrite() 

```
protected includeRewrite() 
```

**Summary**

Include the rewrite include file
The include file will be included from
INCLUDES."rewrites/".PREFIX."_rewrite_include.php

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_addRegexTag" class="anchor"></a>
#### protected addRegexTag() 

```
protected addRegexTag(array  $regex, string  $driver) 
```

**Summary**

Adds the Regular Expression Tags
This will Add Regex Tags, which will be replaced in the
search patterns.

**Description**

Example: %news_id% could be replaced with ([0-9]+) as it must be a number.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $regex  | Array of Tags to be added. |
| <code>string</code> | $driver  | Type or Handler name |




<a name="method_verifyHandlers" class="anchor"></a>
#### protected verifyHandlers() 

```
protected verifyHandlers() 
```

**Summary**

Verify Handlers
This will verify all the added Handlers by checking if they are enabled
or not. The Disabled Handlers are removed from the List and only Enabled
Handlers are kept for working.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_prepareSearchRegex" class="anchor"></a>
#### protected prepareSearchRegex() 

```
protected prepareSearchRegex() 
```

**Summary**

Prepare search regex

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_appendSearchPath" class="anchor"></a>
#### protected appendSearchPath() : string

```
protected appendSearchPath(string  $str) : string
```

**Summary**

Append the BASEDIR Path to Search String
This function will append the BASEDIR path to the Search pattern. This is
required in some cases like when we are on actual php script page and
Permalinks are ON.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $str  | The String |

**Returns:** string


<a name="method_cleanRegex" class="anchor"></a>
#### protected cleanRegex() : string

```
Static protected cleanRegex(string  $regex) : string
```

**Summary**

Clean the REGEX by escaping some characters
This function will escape some characters in the Regex expression

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $regex  | The expression String |

**Returns:** string


<a name="method_handlePermalinkRequests" class="anchor"></a>
#### protected handlePermalinkRequests() 

```
protected handlePermalinkRequests() 
```

**Summary**

Builds the Regular Expressions Patterns for Permalink Translations
This function reads HTML output buffer
This function will create the Regex patterns and will put the built patterns
in $patterns_regex array. This array will then used in preg_match function
to match against current request.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_wrapQuotes" class="anchor"></a>
#### protected wrapQuotes() : string

```
Static protected wrapQuotes(string  $str) : string
```

**Summary**

Wrap a String with Single Quotes (')
This function will wrap a string passed with Single Quotes.

**Description**

Example: mystring will become 'mystring'

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $str  | The String |

**Returns:** string


<a name="method_wrapDoubleQuotes" class="anchor"></a>
#### protected wrapDoubleQuotes() : string

```
Static protected wrapDoubleQuotes(  $str) : string
```

**Summary**

Add compatibalities with double quotes HTML codes for Permalink

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $str  |  |

**Returns:** string


<a name="method_cleanUrl" class="anchor"></a>
#### protected cleanUrl() : string

```
Static protected cleanUrl(string  $string, string  $delimiter = &quot;-&quot;) : string
```

**Summary**

Cleans the URL
This function will clean the URL by removing any unwanted characters from it and
only allowing alphanumeric and - in the URL.

**Description**

This function can be customized according to your needs.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $string  | The URL String |
| <code>string</code> | $delimiter  |  |

**Returns:** string


<a name="method_handleNonSeoUrl" class="anchor"></a>
#### protected handleNonSeoUrl() 

```
protected handleNonSeoUrl() 
```

**Summary**

If Page is Not SEO, Redirect to SEO one

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)




<a name="method_redirect301" class="anchor"></a>
#### protected redirect301() 

```
Static protected redirect301(string  $target, boolean  $debug = FALSE) 
```

**Summary**

Redirect 301 : Moved Permanently Redirect
This function invoked to prevent of caching any kinds of Non SEO URL on render.

**Description**

Let search engine mark as 301 permanently

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $target  | The target URL |
| <code>boolean</code> | $debug  |  |




<a name="method_replaceOtherTags" class="anchor"></a>
#### protected replaceOtherTags() : string

```
protected replaceOtherTags(string  $type, string  $search, string  $replace, array  $matches, string  $matchkey) : string
```

**Summary**

Replace Other Tags in Pattern
This function will replace all the Tags in the Pattern with their suitable found
matches. All the Information is passed to the function and it will replace the
Tags with their respective matches.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Type of Pattern |
| <code>string</code> | $search  | specific Search Pattern |
| <code>string</code> | $replace  | specific Replace Pattern |
| <code>array</code> | $matches  | Array of the Matches found for a specific pattern |
| <code>string</code> | $matchkey  | A Unique matchkey for different matches found for same pattern |

**Returns:** string


<a name="method_getTagPosition" class="anchor"></a>
#### protected getTagPosition() : integer

```
protected getTagPosition(string  $pattern, string  $search) : integer
```

**Summary**

Calculates the Tag Position in a given pattern.

**Description**

This function will calculate the position of a given Tag in a given pattern.
Example: %id% is at 2 position in articles-%title%-%id%

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $pattern  | The Pattern string in which particular Tag will be searched. |
| <code>string</code> | $search  | The Tag which will be searched. |

**Returns:** integer


<a name="method_setWarning" class="anchor"></a>
#### protected setWarning() 

```
protected setWarning(integer  $code, string  $info = &quot;&quot;) 
```

**Summary**

Set Warnings
This function will set Warnings. It will set them by Adding them into
the $this->warnings array.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $code  | The Code Number of the Warning |
| <code>string</code> | $info  | Any other Info to Show along with Warning |




<a name="method_getUniqueIDtag" class="anchor"></a>
#### protected getUniqueIDtag() : string

```
protected getUniqueIDtag(string  $type) : string
```

**Summary**

Get the Tag of the Unique ID type
Example: For news, unique ID should be news_id
So it will return %news_id% because of array("%%news_id" => "news_id")

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $type  | Type or Handler name |

**Returns:** string


<a name="method_makeSearchRegex" class="anchor"></a>
#### protected makeSearchRegex() : string

```
protected makeSearchRegex(string  $pattern, string  $type) : string
```

**Summary**

Builds the Regex pattern for a specific Type string
This function will build the Regex pattern for a specific string, which is
passed to the function.

**Description**

Example: %news_id% could be replaced with ([0-9]+) as it must be a number.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $pattern  | Array of Tags to be added. |
| <code>string</code> | $type  | Type or Handler name |

**Returns:** string


<a name="method_setOutput" class="anchor"></a>
#### protected setOutput() 

```
protected setOutput(  $output) 
```

**Summary**

Entrance to Permalink from PHP Buffer
This function prepares HTML codes to be preg_matched against Permalink Driver
Decode everything

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $output  |  |




<a name="method_cleanString" class="anchor"></a>
#### protected cleanString() : string

```
protected cleanString(  $mystr = &quot;&quot;) : string
```

**Summary**

Clean the URI String for MATCH/AGAINST in MySQL
This function will Clean the string and removes any unwanted characters from it.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $mystr  | - string |

**Returns:** string


<a name="method_addRewrite" class="anchor"></a>
#### private addRewrite() 

```
private addRewrite(string  $include_prefix) 
```

**Summary**

Add the rewrite include file to be included
This will Add new rewrite include file to be included.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\RewriteDriver](../classes/PHPFusion.Rewrite.RewriteDriver.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $include_prefix  | Prefix of the file to be included. |




<a name="method_importPatterns" class="anchor"></a>
#### private importPatterns() 

```
private importPatterns() 
```

**Summary**

Import the Available Patterns from Database
This will Import all the available Patterns for the Handlers
from the Database and put it into $pattern_search and
$pattern_replace array.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_checkAlias" class="anchor"></a>
#### private checkAlias() 

```
private checkAlias() 
```

**Summary**

Checks if there is any matching Alias or not
This function will check if there is any matching Alias for the URI or not.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_getAliasUrl" class="anchor"></a>
#### private getAliasUrl() : mixed&amp;#124;string

```
private getAliasUrl(string  $url, string  $php_url, string  $type) : mixed&amp;#124;string
```

**Summary**

Get Alias URL for Router
This function will return an Array of 2 elements for a specific Alias:
1. The Permalink URL of Alias
2. PHP URL of the Alias

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | The Permalink URL (incomplete) |
| <code>string</code> | $php_url  | The PHP URL (incomplete) |
| <code>string</code> | $type  | Type of Alias |

**Returns:** mixed&#124;string


<a name="method_explodeUrl" class="anchor"></a>
#### private explodeUrl() : array

```
private explodeUrl(string  $url) : array
```

**Summary**

Explodes a URL into Filename and Get Parameters
This function will explode the URL into its Filename and Get Parameters
Example: viewthread.php?thread_id=1&amp;rowstart=20
then :
array[0] => viewthread.php
array[1] => array(
[thread_id] => 1
[rowstart] => 20
)

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | The URL |

**Returns:** array


<a name="method_setVariables" class="anchor"></a>
#### private setVariables() 

```
private setVariables() 
```

**Summary**

Call the Functions to Set GET Parameters and Query String
This function will call the functions to set Server GET parameters
and the QUERY_STRING.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_buildParams" class="anchor"></a>
#### private buildParams() 

```
private buildParams() 
```

**Summary**

Builds the $_GET parameters
This function will build the GET parameters and also the Query String.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_checkAliasPatterns" class="anchor"></a>
#### private checkAliasPatterns() 

```
private checkAliasPatterns() 
```

**Summary**

Checks if there is any matching Alias Pattern or not
This function will check if there is any matching Alias Pattern for the URI or not.

**Description**

Example: If a Thread request is like: "post-your-site-rowstart-20", then it will
try to find any pattern like: "post-your-site-rowstart-%thread_rowstart%"

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_checkPattern" class="anchor"></a>
#### private checkPattern() 

```
private checkPattern() 
```

**Summary**

Builds the Regular Expressions Patterns
This function will create the Regex patterns and will put the built patterns
in $patterns_regex array. This array will then used in preg_match function
to match against current request.

**Description**

Note: Using ^ and $ made us to match exact string so that it doesn't match sub-patterns

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)




<a name="method_displayWarnings" class="anchor"></a>
#### private displayWarnings() 

```
private displayWarnings() 
```

**Summary**

Show Warnings or Debugging Information
This function will show the Warnings or Debugging Information
if Warnings are enabled or if Debug Mode is enabled.

**Details:**
* Inherited From: [\PHPFusion\Rewrite\Router](../classes/PHPFusion.Rewrite.Router.md)





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
