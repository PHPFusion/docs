# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Update
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Infusions

---
### Constants
* No constants found
---
### Properties
* [protected $current_version](../classes/PHPFusion.Update.md#property_current_version)
* [private $locale](../classes/PHPFusion.Update.md#property_locale)
* [private $instance](../classes/PHPFusion.Installer.Infusions.md#property_instance)
* [private $inf](../classes/PHPFusion.Installer.Infusions.md#property_inf)
* [private $temp_dir](../classes/PHPFusion.Update.md#property_temp_dir)
* [private $install_dir](../classes/PHPFusion.Update.md#property_install_dir)
* [private $update_url](../classes/PHPFusion.Update.md#property_update_url)
* [private $update_file](../classes/PHPFusion.Update.md#property_update_file)
* [private $lang_url](../classes/PHPFusion.Update.md#property_lang_url)
* [private $available_languages](../classes/PHPFusion.Update.md#property_available_languages)
* [private $latest_version](../classes/PHPFusion.Update.md#property_latest_version)
* [private $update](../classes/PHPFusion.Update.md#property_update)
* [private $messages](../classes/PHPFusion.Update.md#property_messages)
---
### Methods
* [public loadConfiguration()](../classes/PHPFusion.Installer.Infusions.md#method_loadConfiguration)
* [public getInstance()](../classes/PHPFusion.Installer.Infusions.md#method_getInstance)
* [public loadInfusion()](../classes/PHPFusion.Installer.Infusions.md#method_loadInfusion)
* [public loadUpgrade()](../classes/PHPFusion.Installer.Infusions.md#method_loadUpgrade)
* [public infuse()](../classes/PHPFusion.Installer.Infusions.md#method_infuse)
* [public defuse()](../classes/PHPFusion.Installer.Infusions.md#method_defuse)
* [public __construct()](../classes/PHPFusion.Update.md#method___construct)
* [public setUpdateUrl()](../classes/PHPFusion.Update.md#method_setUpdateUrl)
* [public setUpdateFile()](../classes/PHPFusion.Update.md#method_setUpdateFile)
* [public getUpdateUrl()](../classes/PHPFusion.Update.md#method_getUpdateUrl)
* [public getLatestVersion()](../classes/PHPFusion.Update.md#method_getLatestVersion)
* [public checkUpdate()](../classes/PHPFusion.Update.md#method_checkUpdate)
* [public newVersionAvailable()](../classes/PHPFusion.Update.md#method_newVersionAvailable)
* [public getEnabledLanguages()](../classes/PHPFusion.Update.md#method_getEnabledLanguages)
* [public updateLanguages()](../classes/PHPFusion.Update.md#method_updateLanguages)
* [public downloadLanguage()](../classes/PHPFusion.Update.md#method_downloadLanguage)
* [public upgradeCms()](../classes/PHPFusion.Update.md#method_upgradeCms)
* [public getAvailableLanguages()](../classes/PHPFusion.Update.md#method_getAvailableLanguages)
* [public ajaxChecker()](../classes/PHPFusion.Update.md#method_ajaxChecker)
* [public getMessages()](../classes/PHPFusion.Update.md#method_getMessages)
* [protected adminpanel_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_adminpanel_infuse)
* [protected dropcol_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_dropcol_infuse)
* [protected sitelink_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_sitelink_infuse)
* [protected mlt_insertdbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_insertdbrow_infuse)
* [protected mlt_adminpanel_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_adminpanel_infuse)
* [protected mlt_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_mlt_infuse)
* [protected altertable_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_altertable_infuse)
* [protected updatedbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_updatedbrow_infuse)
* [protected newtable_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_newtable_infuse)
* [protected newcol_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_newcol_infuse)
* [protected insertdbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_insertdbrow_infuse)
* [protected deldbrow_infuse()](../classes/PHPFusion.Installer.Infusions.md#method_deldbrow_infuse)
* [protected isValidUrl()](../classes/PHPFusion.Update.md#method_isValidUrl)
* [protected downloadCurl()](../classes/PHPFusion.Update.md#method_downloadCurl)
* [protected downloadZip()](../classes/PHPFusion.Update.md#method_downloadZip)
* [protected extractFiles()](../classes/PHPFusion.Update.md#method_extractFiles)
* [protected doUpgradeBatch()](../classes/PHPFusion.Update.md#method_doUpgradeBatch)
* [private copyFiles()](../classes/PHPFusion.Update.md#method_copyFiles)
* [private doDbUpgrade()](../classes/PHPFusion.Update.md#method_doDbUpgrade)
* [private updateCoreFiles()](../classes/PHPFusion.Update.md#method_updateCoreFiles)
* [private setMessage()](../classes/PHPFusion.Update.md#method_setMessage)
* [private setError()](../classes/PHPFusion.Update.md#method_setError)
---
### Details
* File: [classes\PHPFusion\Update.php](../files/classes.PHPFusion.Update.md)
* Package: Default
* Class Hierarchy: 
  * [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
  * \PHPFusion\Update
---
## Properties
<a name="property_current_version"></a>
#### protected $current_version : string
---
**Type:** string

**Details:**


<a name="property_locale"></a>
#### private $locale : array|string
---
**Type:** array|string

**Details:**


<a name="property_instance"></a>
#### private $instance : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)


<a name="property_inf"></a>
#### private $inf : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)


<a name="property_temp_dir"></a>
#### private $temp_dir : string
---
**Summary**

Temporary directory for downloads

**Type:** string

**Details:**


<a name="property_install_dir"></a>
#### private $install_dir : string
---
**Summary**

Install directory

**Type:** string

**Details:**


<a name="property_update_url"></a>
#### private $update_url : string
---
**Summary**

Url to the update folder on the server

**Type:** string

**Details:**


<a name="property_update_file"></a>
#### private $update_file : string
---
**Summary**

Version filename on the server

**Type:** string

**Details:**


<a name="property_lang_url"></a>
#### private $lang_url : string
---
**Summary**

The URL from which the translations will be downloaded

**Type:** string

**Details:**


<a name="property_available_languages"></a>
#### private $available_languages : string
---
**Summary**

List of available languages

**Type:** string

**Details:**


<a name="property_latest_version"></a>
#### private $latest_version : string
---
**Type:** string

**Details:**


<a name="property_update"></a>
#### private $update : array
---
**Type:** array

**Details:**


<a name="property_messages"></a>
#### private $messages : array
---
**Type:** array

**Details:**



---
## Methods
<a name="method_loadConfiguration" class="anchor"></a>
#### public loadConfiguration() 

```
Static public loadConfiguration() 
```

**Summary**

Version 7 compatible infusions load constants.

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)




<a name="method_getInstance" class="anchor"></a>
#### public getInstance() : null&amp;#124;static

```
Static public getInstance() : null&amp;#124;static
```

**Summary**

Get Instance

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)

**Returns:** null&#124;static


<a name="method_loadInfusion" class="anchor"></a>
#### public loadInfusion() : array

```
Static public loadInfusion(string  $folder) : array
```

**Summary**

Load Infusion according to Infusion Standard Developer Kit

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  |  |

**Returns:** array


<a name="method_loadUpgrade" class="anchor"></a>
#### public loadUpgrade() : array

```
Static public loadUpgrade(string  $folder, string  $upgrade_file_path) : array
```

**Summary**

Load upgrade folder

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  |  |
| <code>string</code> | $upgrade_file_path  |  |

**Returns:** array


<a name="method_infuse" class="anchor"></a>
#### public infuse() : mixed&amp;#124;null

```
public infuse(  $folder) : mixed&amp;#124;null
```

**Summary**

Execute Installation according to Infusion Standard Developer Kit

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
* Uses:
 * [adminpanel_infuse]()
 * [dropcol_infuse]()
 * [sitelink_infuse]()
 * [mlt_insertdbrow_infuse]()
 * [mlt_adminpanel_infuse]()
 * [mlt_infuse]()
 * [altertable_infuse]()
 * [updatedbrow_infuse]()
 * [newtable_infuse]()
 * [newcol_infuse]()
 * [insertdbrow_infuse]()
 * [deldbrow_infuse]()
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $folder  |  |

**Returns:** mixed&#124;null


<a name="method_defuse" class="anchor"></a>
#### public defuse() 

```
public defuse(  $folder) 
```

**Summary**

Defuse

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $folder  |  |




<a name="method___construct" class="anchor"></a>
#### public __construct() 

```
public __construct() 
```

**Summary**

AutoUpdate constructor

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)




<a name="method_setUpdateUrl" class="anchor"></a>
#### public setUpdateUrl() 

```
public setUpdateUrl(string  $update_url) 
```

**Summary**

Set the update url

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $update_url  |  |




<a name="method_setUpdateFile" class="anchor"></a>
#### public setUpdateFile() 

```
public setUpdateFile(string  $update_file) 
```

**Summary**

Set the update file

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $update_file  |  |




<a name="method_getUpdateUrl" class="anchor"></a>
#### public getUpdateUrl() : string

```
public getUpdateUrl() : string
```

**Summary**

Get the update url

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** string


<a name="method_getLatestVersion" class="anchor"></a>
#### public getLatestVersion() : string

```
public getLatestVersion() : string
```

**Summary**

Get the number of the latest version

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** string


<a name="method_checkUpdate" class="anchor"></a>
#### public checkUpdate() : array&amp;#124;boolean

```
public checkUpdate(false  $return_version = FALSE) : array&amp;#124;boolean
```

**Summary**

Check for a new version

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>false</code> | $return_version  |  |

**Returns:** array&#124;boolean


<a name="method_newVersionAvailable" class="anchor"></a>
#### public newVersionAvailable() : boolean

```
public newVersionAvailable() : boolean
```

**Summary**

Check if a new version is available.

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** boolean


<a name="method_getEnabledLanguages" class="anchor"></a>
#### public getEnabledLanguages() : false&amp;#124;array&lt;mixed,string&gt;

```
public getEnabledLanguages() : false&amp;#124;array&lt;mixed,string&gt;
```

**Summary**

Get enabled languages

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** false&#124;array&lt;mixed,string&gt;


<a name="method_updateLanguages" class="anchor"></a>
#### public updateLanguages() : boolean

```
public updateLanguages() : boolean
```

**Summary**

Update languages

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** boolean


<a name="method_downloadLanguage" class="anchor"></a>
#### public downloadLanguage() : boolean

```
public downloadLanguage(string  $language) : boolean
```

**Summary**

Download language

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $language  |  |

**Returns:** boolean


<a name="method_upgradeCms" class="anchor"></a>
#### public upgradeCms() 

```
public upgradeCms() 
```

**Summary**

Run upgrade

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)




<a name="method_getAvailableLanguages" class="anchor"></a>
#### public getAvailableLanguages() : array&amp;#124;false

```
public getAvailableLanguages() : array&amp;#124;false
```

**Summary**

Get available languages

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** array&#124;false


<a name="method_ajaxChecker" class="anchor"></a>
#### public ajaxChecker() 

```
public ajaxChecker() 
```

**Summary**

Ajax checker

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)




<a name="method_getMessages" class="anchor"></a>
#### public getMessages() : array

```
public getMessages() : array
```

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** array


<a name="method_adminpanel_infuse" class="anchor"></a>
#### protected adminpanel_infuse() : boolean

```
Static protected adminpanel_infuse(array  $inf) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_dropcol_infuse" class="anchor"></a>
#### protected dropcol_infuse() : boolean

```
protected dropcol_infuse(array  $inf) : boolean
```

**Summary**

Drop column

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_sitelink_infuse" class="anchor"></a>
#### protected sitelink_infuse() : boolean

```
protected sitelink_infuse(array  $inf) : boolean
```

**Summary**

Add Sitelinks

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_insertdbrow_infuse" class="anchor"></a>
#### protected mlt_insertdbrow_infuse() : boolean

```
protected mlt_insertdbrow_infuse(array  $inf) : boolean
```

**Summary**

Register Multilang rights

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_adminpanel_infuse" class="anchor"></a>
#### protected mlt_adminpanel_infuse() : boolean

```
protected mlt_adminpanel_infuse(array  $inf) : boolean
```

**Summary**

Register Multilang Admin Pages

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_mlt_infuse" class="anchor"></a>
#### protected mlt_infuse() : boolean

```
protected mlt_infuse(array  $inf) : boolean
```

**Summary**

Multilanguage Insert Rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_altertable_infuse" class="anchor"></a>
#### protected altertable_infuse() : boolean

```
protected altertable_infuse(array  $inf) : boolean
```

**Summary**

Change table structure

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_updatedbrow_infuse" class="anchor"></a>
#### protected updatedbrow_infuse() : boolean

```
protected updatedbrow_infuse(array  $inf) : boolean
```

**Summary**

Update Row Record

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_newtable_infuse" class="anchor"></a>
#### protected newtable_infuse() : boolean

```
protected newtable_infuse(array  $inf) : boolean
```

**Summary**

Install New Table

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_newcol_infuse" class="anchor"></a>
#### protected newcol_infuse() : boolean

```
protected newcol_infuse(array  $inf) : boolean
```

**Summary**

Insert New Column

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_insertdbrow_infuse" class="anchor"></a>
#### protected insertdbrow_infuse() : boolean

```
protected insertdbrow_infuse(array  $inf) : boolean
```

**Summary**

Insert Rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_deldbrow_infuse" class="anchor"></a>
#### protected deldbrow_infuse() : boolean

```
protected deldbrow_infuse(array  $inf) : boolean
```

**Summary**

Delete rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $inf  |  |

**Returns:** boolean


<a name="method_isValidUrl" class="anchor"></a>
#### protected isValidUrl() : boolean

```
protected isValidUrl(string  $url) : boolean
```

**Summary**

Check if url is valid

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  |  |

**Returns:** boolean


<a name="method_downloadCurl" class="anchor"></a>
#### protected downloadCurl() : string&amp;#124;false

```
protected downloadCurl(string  $url) : string&amp;#124;false
```

**Summary**

Download file via curl

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | URL to file |

**Returns:** string&#124;false


<a name="method_downloadZip" class="anchor"></a>
#### protected downloadZip() : boolean

```
protected downloadZip(string  $update_url, string  $update_file) : boolean
```

**Summary**

Download update

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $update_url  | Url where to download from |
| <code>string</code> | $update_file  | Path where to save the download |

**Returns:** boolean


<a name="method_extractFiles" class="anchor"></a>
#### protected extractFiles() : boolean

```
protected extractFiles(string  $zip_file, string  $dest) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $zip_file  | Path to the update file |
| <code>string</code> | $dest  | Destination directory |

**Returns:** boolean


<a name="method_doUpgradeBatch" class="anchor"></a>
#### protected doUpgradeBatch() : boolean

```
protected doUpgradeBatch(  $method,   $code_array) : boolean
```

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
* Uses:
 * [adminpanel_infuse]()
 * [dropcol_infuse]()
 * [sitelink_infuse]()
 * [mlt_insertdbrow_infuse]()
 * [mlt_adminpanel_infuse]()
 * [mlt_infuse]()
 * [altertable_infuse]()
 * [updatedbrow_infuse]()
 * [newtable_infuse]()
 * [newcol_infuse]()
 * [insertdbrow_infuse]()
 * [deldbrow_infuse]()
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $method  |  |
| <code></code> | $code_array  |  |

**Returns:** boolean


<a name="method_copyFiles" class="anchor"></a>
#### private copyFiles() 

```
private copyFiles(  $source,   $target) 
```

**Summary**

Copy files

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $source  |  |
| <code></code> | $target  |  |




<a name="method_doDbUpgrade" class="anchor"></a>
#### private doDbUpgrade() : boolean

```
private doDbUpgrade() : boolean
```

**Summary**

Run upgrade scripts

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** boolean


<a name="method_updateCoreFiles" class="anchor"></a>
#### private updateCoreFiles() : boolean

```
private updateCoreFiles() : boolean
```

**Summary**

Update core

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)

**Returns:** boolean


<a name="method_setMessage" class="anchor"></a>
#### private setMessage() 

```
private setMessage(  $message) 
```

**Summary**

Set message

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $message  |  |




<a name="method_setError" class="anchor"></a>
#### private setError() 

```
private setError(  $message) 
```

**Details:**
* Inherited From: [\PHPFusion\Update](../classes/PHPFusion.Update.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $message  |  |





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
