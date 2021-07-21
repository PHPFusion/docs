# [PHPFusion Docs](../home.md)

# Class: \SqlHandler
### Namespace: [\](../namespaces/default.md)
---
---
### Constants
* No constants found
---
### Properties
---
### Methods
* [public add_column()](../classes/SqlHandler.md#method_add_column)
* [public drop_column()](../classes/SqlHandler.md#method_drop_column)
* [public build_table()](../classes/SqlHandler.md#method_build_table)
* [public transfer_table()](../classes/SqlHandler.md#method_transfer_table)
* [public drop_table()](../classes/SqlHandler.md#method_drop_table)
* [public rename_column()](../classes/SqlHandler.md#method_rename_column)
* [public move_column()](../classes/SqlHandler.md#method_move_column)
---
### Details
* File: [sqlhandler.inc.php](../files/sqlhandler.inc.md)
* Package: Default
* Class Hierarchy:
  * \SqlHandler

---
## Methods
<a name="method_add_column" class="anchor"></a>
#### public add_column() 

```
Static public add_column(string  $table_name, string  $new_column_name, string  $field_attributes) 
```

**Summary**

Add column to a specific table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $new_column_name  |  |
| <code>string</code> | $field_attributes  |  |




<a name="method_drop_column" class="anchor"></a>
#### public drop_column() 

```
Static public drop_column(string  $table_name, string  $old_column_name) 
```

**Summary**

Drop column of a table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $old_column_name  |  |




<a name="method_build_table" class="anchor"></a>
#### public build_table() : mixed

```
Static public build_table(string  $new_table, string  $primary_column) : mixed
```

**Summary**

Build a new table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $new_table  |  |
| <code>string</code> | $primary_column  |  |

**Returns:** mixed


<a name="method_transfer_table" class="anchor"></a>
#### public transfer_table() 

```
Static public transfer_table(string  $old_table, string  $new_table) 
```

**Summary**

Move old table to new table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |
| <code>string</code> | $new_table  |  |




<a name="method_drop_table" class="anchor"></a>
#### public drop_table() 

```
Static public drop_table(string  $old_table) 
```

**Summary**

Drop table.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |




<a name="method_rename_column" class="anchor"></a>
#### public rename_column() 

```
Static public rename_column(string  $table_name, string  $old_column_name, string  $new_column_name, string  $field_attributes) 
```

**Summary**

Rename column name.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_name  |  |
| <code>string</code> | $old_column_name  |  |
| <code>string</code> | $new_column_name  |  |
| <code>string</code> | $field_attributes  |  |




<a name="method_move_column" class="anchor"></a>
#### public move_column() 

```
Static public move_column(string  $old_table, string  $new_table, string  $column_name) 
```

**Summary**

Move a single column from one table to another.

**Details:**
* Inherited From: [\SqlHandler](../classes/SqlHandler.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $old_table  |  |
| <code>string</code> | $new_table  |  |
| <code>string</code> | $column_name  |  |





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
