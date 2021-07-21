# [PHPFusion Docs](../home.md)

# Class: \PHPFusion\Installer\Batch
### Namespace: [\PHPFusion\Installer](../namespaces/PHPFusion.Installer.md)
---
**Summary:**

Class Batch_Core

**Description:**

Batching of the installation process
* PHPFusion will compare existing tables with the package contents and build
according to identified requirements of a non-destructive approach.

- Should the table is missing, the batch process will auto create the table.
- Should the table is found, and the batch process will check against table columns and create new column..
- Should the table is of the wrong type, to alter the type.

The batch will also generate differences in a log in the end of the batch run.

---
### Constants
* [ STEP_INTRO](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_INTRO)
* [ STEP_PERMISSIONS](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_PERMISSIONS)
* [ STEP_DB_SETTINGS_FORM](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_DB_SETTINGS_FORM)
* [ STEP_DB_SETTINGS_SAVE](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_DB_SETTINGS_SAVE)
* [ STEP_PRIMARY_ADMIN_FORM](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_PRIMARY_ADMIN_FORM)
* [ STEP_PRIMARY_ADMIN_SAVE](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_PRIMARY_ADMIN_SAVE)
* [ STEP_INFUSIONS](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_INFUSIONS)
* [ STEP_SETUP_COMPLETE](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_SETUP_COMPLETE)
* [ STEP_EXIT](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_EXIT)
* [ STEP_TRANSFER](../classes/PHPFusion.Installer.InstallCore.md#constant_STEP_TRANSFER)
* [ BUILD_VERSION](../classes/PHPFusion.Installer.InstallCore.md#constant_BUILD_VERSION)
* [ INSTALLER_ALGO](../classes/PHPFusion.Installer.InstallCore.md#constant_INSTALLER_ALGO)
* [ USER_RIGHTS_SA](../classes/PHPFusion.Installer.InstallCore.md#constant_USER_RIGHTS_SA)
* [ FUSION_TABLE_COLLATION](../classes/PHPFusion.Installer.Batch.md#constant_FUSION_TABLE_COLLATION)
* [ CREATE_TABLE_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_CREATE_TABLE_STATEMENT)
* [ TABLE_ATTR_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_TABLE_ATTR_STATEMENT)
* [ ADD_COLUMN_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_ADD_COLUMN_STATEMENT)
* [ ALTER_COLUMN_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_ALTER_COLUMN_STATEMENT)
* [ INSERT_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_INSERT_STATEMENT)
* [ UPDATE_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_UPDATE_STATEMENT)
* [ ADD_INDEX_STATEMENT](../classes/PHPFusion.Installer.Batch.md#constant_ADD_INDEX_STATEMENT)
---
### Properties
* [protected $localeset](../classes/PHPFusion.Installer.InstallCore.md#property_localeset)
* [protected $allow_delete](../classes/PHPFusion.Installer.InstallCore.md#property_allow_delete)
* [protected $step](../classes/PHPFusion.Installer.InstallCore.md#property_step)
* [protected $connection](../classes/PHPFusion.Installer.InstallCore.md#property_connection)
* [protected $site_data](../classes/PHPFusion.Installer.InstallCore.md#property_site_data)
* [protected $user_data](../classes/PHPFusion.Installer.InstallCore.md#property_user_data)
* [protected $locale_files](../classes/PHPFusion.Installer.InstallCore.md#property_locale_files)
* [protected $document](../classes/PHPFusion.Installer.InstallCore.md#property_document)
* [private $locale](../classes/PHPFusion.Installer.Infusions.md#property_locale)
* [private $setup_instance](../classes/PHPFusion.Installer.InstallCore.md#property_setup_instance)
* [private $config](../classes/PHPFusion.Installer.InstallCore.md#property_config)
* [private $instance](../classes/PHPFusion.Installer.Infusions.md#property_instance)
* [private $inf](../classes/PHPFusion.Installer.Infusions.md#property_inf)
* [private $batch](../classes/PHPFusion.Installer.Batch.md#property_batch)
* [private $table_name](../classes/PHPFusion.Installer.Batch.md#property_table_name)
* [private $table_cols](../classes/PHPFusion.Installer.Batch.md#property_table_cols)
* [private $required_default](../classes/PHPFusion.Installer.Batch.md#property_required_default)
* [private $runtime_results](../classes/PHPFusion.Installer.Batch.md#property_runtime_results)
* [private $schema_storage](../classes/PHPFusion.Installer.Batch.md#property_schema_storage)
* [private $upgrade_runtime](../classes/PHPFusion.Installer.Batch.md#property_upgrade_runtime)
---
### Methods
* [public getInstallInstance()](../classes/PHPFusion.Installer.InstallCore.md#method_getInstallInstance)
* [public fusionGetConfig()](../classes/PHPFusion.Installer.InstallCore.md#method_fusionGetConfig)
* [public createRandomPrefix()](../classes/PHPFusion.Installer.InstallCore.md#method_createRandomPrefix)
* [public installPhpfusion()](../classes/PHPFusion.Installer.InstallCore.md#method_installPhpfusion)
* [public loadConfiguration()](../classes/PHPFusion.Installer.Infusions.md#method_loadConfiguration)
* [public getInstance()](../classes/PHPFusion.Installer.Batch.md#method_getInstance)
* [public loadInfusion()](../classes/PHPFusion.Installer.Infusions.md#method_loadInfusion)
* [public loadUpgrade()](../classes/PHPFusion.Installer.Infusions.md#method_loadUpgrade)
* [public infuse()](../classes/PHPFusion.Installer.Infusions.md#method_infuse)
* [public defuse()](../classes/PHPFusion.Installer.Infusions.md#method_defuse)
* [public batchRuntime()](../classes/PHPFusion.Installer.Batch.md#method_batchRuntime)
* [public batchInsertRows()](../classes/PHPFusion.Installer.Batch.md#method_batchInsertRows)
* [public checkUpgrades()](../classes/PHPFusion.Installer.Batch.md#method_checkUpgrades)
* [protected __construct()](../classes/PHPFusion.Installer.InstallCore.md#method___construct)
* [protected installerStep()](../classes/PHPFusion.Installer.InstallCore.md#method_installerStep)
* [protected setEmptyPrefix()](../classes/PHPFusion.Installer.InstallCore.md#method_setEmptyPrefix)
* [protected servePage()](../classes/PHPFusion.Installer.InstallCore.md#method_servePage)
* [protected tableCheck()](../classes/PHPFusion.Installer.InstallCore.md#method_tableCheck)
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
* [private verifyRequirements()](../classes/PHPFusion.Installer.InstallCore.md#method_verifyRequirements)
* [private detectSystemUpgrade()](../classes/PHPFusion.Installer.InstallCore.md#method_detectSystemUpgrade)
* [private getInstallerContent()](../classes/PHPFusion.Installer.InstallCore.md#method_getInstallerContent)
* [private __clone()](../classes/PHPFusion.Installer.InstallCore.md#method___clone)
* [private checkExistingTable()](../classes/PHPFusion.Installer.Batch.md#method_checkExistingTable)
* [private getTableSchema()](../classes/PHPFusion.Installer.Batch.md#method_getTableSchema)
* [private getTableAttr()](../classes/PHPFusion.Installer.Batch.md#method_getTableAttr)
* [private createNewTable()](../classes/PHPFusion.Installer.Batch.md#method_createNewTable)
* [private batchCreateTable()](../classes/PHPFusion.Installer.Batch.md#method_batchCreateTable)
---
### Details
* File: [classes\PHPFusion\Installer\Batch.php](../files/classes.PHPFusion.Installer.Batch.md)
* Package: Installer\Lib
* Class Hierarchy:  
  * [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)
  * [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)
  * \PHPFusion\Installer\Batch
---
## Constants
<a name="constant_STEP_INTRO" class="anchor"></a>
###### STEP_INTROInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_INTRO = 1
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_PERMISSIONS" class="anchor"></a>
###### STEP_PERMISSIONSInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_PERMISSIONS = 2
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_DB_SETTINGS_FORM" class="anchor"></a>
###### STEP_DB_SETTINGS_FORMInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_DB_SETTINGS_FORM = 3
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_DB_SETTINGS_SAVE" class="anchor"></a>
###### STEP_DB_SETTINGS_SAVEInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_DB_SETTINGS_SAVE = 4
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_PRIMARY_ADMIN_FORM" class="anchor"></a>
###### STEP_PRIMARY_ADMIN_FORMInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_PRIMARY_ADMIN_FORM = '5'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_PRIMARY_ADMIN_SAVE" class="anchor"></a>
###### STEP_PRIMARY_ADMIN_SAVEInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_PRIMARY_ADMIN_SAVE = '5'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_INFUSIONS" class="anchor"></a>
###### STEP_INFUSIONSInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_INFUSIONS = 6
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_SETUP_COMPLETE" class="anchor"></a>
###### STEP_SETUP_COMPLETEInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_SETUP_COMPLETE = 7
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_EXIT" class="anchor"></a>
###### STEP_EXITInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_EXIT = 8
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_STEP_TRANSFER" class="anchor"></a>
###### STEP_TRANSFERInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
STEP_TRANSFER = 9
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_BUILD_VERSION" class="anchor"></a>
###### BUILD_VERSIONInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
BUILD_VERSION = '9.10.00'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_INSTALLER_ALGO" class="anchor"></a>
###### INSTALLER_ALGOInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
INSTALLER_ALGO = 'sha256'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_USER_RIGHTS_SA" class="anchor"></a>
###### USER_RIGHTS_SAInherited from [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

```
USER_RIGHTS_SA = 'AD.APWR.B.BB.C.CP.DB.ERRO.FM.I.IM.IP.LANG.M.MAIL.MI.P.PI.PL.ROB.S1.S2.S4.S6.S7.S9.S12.SB.SL.SM.TS.U.UF.UG.UL'
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_FUSION_TABLE_COLLATION" class="anchor"></a>
###### FUSION_TABLE_COLLATION
```
FUSION_TABLE_COLLATION = "ENGINE=MyISAM DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_unicode_ci;"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_CREATE_TABLE_STATEMENT" class="anchor"></a>
###### CREATE_TABLE_STATEMENT
```
CREATE_TABLE_STATEMENT = "CREATE TABLE {%table%} ({%table_attr%}) {%collation%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_TABLE_ATTR_STATEMENT" class="anchor"></a>
###### TABLE_ATTR_STATEMENT
```
TABLE_ATTR_STATEMENT = "{%col_name%}{%type%}{%length%}{%unsigned%}{%null%}{%default%}{%auto_increment%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_ADD_COLUMN_STATEMENT" class="anchor"></a>
###### ADD_COLUMN_STATEMENT
```
ADD_COLUMN_STATEMENT = "ALTER TABLE {%table%} ADD COLUMN {%table_attr%} AFTER {%column_before%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_ALTER_COLUMN_STATEMENT" class="anchor"></a>
###### ALTER_COLUMN_STATEMENT
```
ALTER_COLUMN_STATEMENT = "ALTER TABLE {%table%} MODIFY COLUMN {%table_attr%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_INSERT_STATEMENT" class="anchor"></a>
###### INSERT_STATEMENT
```
INSERT_STATEMENT = "INSERT INTO {%table%} {%key%} VALUES {%values%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_UPDATE_STATEMENT" class="anchor"></a>
###### UPDATE_STATEMENT
```
UPDATE_STATEMENT = "UPDATE {%table%} SET {%values%} WHERE {%where%}"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

<a name="constant_ADD_INDEX_STATEMENT" class="anchor"></a>
###### ADD_INDEX_STATEMENT
```
ADD_INDEX_STATEMENT = "ALTER TABLE {%table%} ADD INDEX {%column_name%} ({%column_name%})"
```

| Tag | Version | Desc |
| --- | ------- | ---- |

---
## Properties
<a name="property_localeset"></a>
#### protected $localeset : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_allow_delete"></a>
#### protected $allow_delete : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_step"></a>
#### protected $step : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_connection"></a>
#### protected $connection : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_site_data"></a>
#### protected $site_data : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_user_data"></a>
#### protected $user_data : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_locale_files"></a>
#### protected $locale_files : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_document"></a>
#### protected $document : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_locale"></a>
#### private $locale : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md)


<a name="property_setup_instance"></a>
#### private $setup_instance : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


<a name="property_config"></a>
#### private $config : 
---
**Type:** 

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)


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


<a name="property_batch"></a>
#### private $batch : 
---
**Type:** 

**Details:**


<a name="property_table_name"></a>
#### private $table_name : 
---
**Type:** 

**Details:**


<a name="property_table_cols"></a>
#### private $table_cols : 
---
**Type:** 

**Details:**


<a name="property_required_default"></a>
#### private $required_default : 
---
**Type:** 

**Details:**


<a name="property_runtime_results"></a>
#### private $runtime_results : 
---
**Type:** 

**Details:**


<a name="property_schema_storage"></a>
#### private $schema_storage : 
---
**Type:** 

**Details:**


<a name="property_upgrade_runtime"></a>
#### private $upgrade_runtime : 
---
**Summary**

Use Infusions Core installer to perform upgrades

**Type:** 

**Details:**



---
## Methods
<a name="method_getInstallInstance" class="anchor"></a>
#### public getInstallInstance() : null&amp;#124;static

```
Static public getInstallInstance() : null&amp;#124;static
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

**Returns:** null&#124;static


<a name="method_fusionGetConfig" class="anchor"></a>
#### public fusionGetConfig() : array

```
Static public fusionGetConfig(string  $config_path) : array
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $config_path  |  |

**Returns:** array


<a name="method_createRandomPrefix" class="anchor"></a>
#### public createRandomPrefix() : string

```
Static public createRandomPrefix(integer  $length = 5) : string
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $length  |  |

**Returns:** string


<a name="method_installPhpfusion" class="anchor"></a>
#### public installPhpfusion() 

```
public installPhpfusion() 
```

**Summary**

Install PHPFusion

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




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
#### public getInstance() : static

```
Static public getInstance() : static
```

**Summary**

Return the instance for the Batcher

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)

**Returns:** static


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




<a name="method_batchRuntime" class="anchor"></a>
#### public batchRuntime() : null

```
public batchRuntime(null  $key = NULL) : null
```

**Summary**

Get the runtime results

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>null</code> | $key  |  |

**Returns:** null


<a name="method_batchInsertRows" class="anchor"></a>
#### public batchInsertRows() : null&amp;#124;string

```
Static public batchInsertRows(string  $table_name, string  $localeset) : null&amp;#124;string
```

**Summary**

Add default row records

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $localeset  |  |

**Returns:** null&#124;string


<a name="method_checkUpgrades" class="anchor"></a>
#### public checkUpgrades() : array

```
public checkUpgrades() : array
```

**Summary**

Checks for Upgrade Files

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)

**Returns:** array


<a name="method___construct" class="anchor"></a>
#### protected __construct() 

```
protected __construct() 
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




<a name="method_installerStep" class="anchor"></a>
#### protected installerStep() 

```
Static protected installerStep(string  $step = &#039;auto&#039;) 
```

**Summary**

Set the current installer steps.

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $step  |  |




<a name="method_setEmptyPrefix" class="anchor"></a>
#### protected setEmptyPrefix() 

```
Static protected setEmptyPrefix() 
```

**Summary**

Set empty prefix

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




<a name="method_servePage" class="anchor"></a>
#### protected servePage() : static

```
Static protected servePage() : static
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

**Returns:** static


<a name="method_tableCheck" class="anchor"></a>
#### protected tableCheck() 

```
protected tableCheck() 
```

**Summary**

Installer system checks
Redirect to step 1 if the database has been intentionally dropped during the installation.

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




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


<a name="method_verifyRequirements" class="anchor"></a>
#### private verifyRequirements() 

```
Static private verifyRequirements() 
```

**Summary**

Check the server minimum requirements

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




<a name="method_detectSystemUpgrade" class="anchor"></a>
#### private detectSystemUpgrade() 

```
Static private detectSystemUpgrade() 
```

**Summary**

Detect system upgrade

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




<a name="method_getInstallerContent" class="anchor"></a>
#### private getInstallerContent() : false&amp;#124;string&amp;#124;null

```
private getInstallerContent() : false&amp;#124;string&amp;#124;null
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)

**Returns:** false&#124;string&#124;null


<a name="method___clone" class="anchor"></a>
#### private __clone() 

```
private __clone() 
```

**Details:**
* Inherited From: [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md)




<a name="method_checkExistingTable" class="anchor"></a>
#### private checkExistingTable() 

```
private checkExistingTable() 
```

**Summary**

When table exists, need to be checked for data-types consistencies and column name consistencies

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)




<a name="method_getTableSchema" class="anchor"></a>
#### private getTableSchema() : null

```
private getTableSchema(string  $table_name) : null
```

**Summary**

Fetches Existing Database Table Schema for comparisons

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |

**Returns:** null


<a name="method_getTableAttr" class="anchor"></a>
#### private getTableAttr() : string

```
private getTableAttr(string  $col_name, array  $col_attr) : string
```

**Summary**

Get table column data-type attributes

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $col_name  |  |
| <code>array</code> | $col_attr  |  |

**Returns:** string


<a name="method_createNewTable" class="anchor"></a>
#### private createNewTable() 

```
private createNewTable() 
```

**Summary**

Auto function - Table does not exist, and create new table and rows

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)




<a name="method_batchCreateTable" class="anchor"></a>
#### private batchCreateTable() : string

```
private batchCreateTable() : string
```

**Summary**

Create codes generation

**Details:**
* Inherited From: [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md)

**Returns:** string



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
