# [PHPFusion Docs](../home.md)

# Namespace: \PHPFusion\Installer
## Parent: [\PHPFusion](../namespaces/PHPFusion.md)
### Namespaces
* [\PHPFusion\Installer\Lib](../namespaces/PHPFusion.Installer.Lib.md)
* [\PHPFusion\Installer\Steps](../namespaces/PHPFusion.Installer.Steps.md)
### Classes
| Name | Summary |
| ---- | ------- |
| [\PHPFusion\Installer\Batch](../classes/PHPFusion.Installer.Batch.md) | Class Batch_Core |
| [\PHPFusion\Installer\Console](../classes/PHPFusion.Installer.Console.md) | Class InstallCore |
| [\PHPFusion\Installer\Infusions](../classes/PHPFusion.Installer.Infusions.md) | Class Infusions |
| [\PHPFusion\Installer\InstallCore](../classes/PHPFusion.Installer.InstallCore.md) | Class InstallCore |
| [\PHPFusion\Installer\Requirements](../classes/PHPFusion.Installer.Requirements.md) | Class Requirements
The requirements checks on server system |
### Functions
<a name="method_check_table" class="anchor"></a>
####  check_table() : integer

```
 check_table(string  $db_prefix) : integer
```

**Details:**
* File: [classes\PHPFusion\Installer\Requirements.php](../files/classes.PHPFusion.Installer.Requirements.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db_prefix  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_test_table" class="anchor"></a>
####  test_table() : boolean

```
 test_table(string  $db_prefix) : boolean
```

**Details:**
* File: [classes\PHPFusion\Installer\Requirements.php](../files/classes.PHPFusion.Installer.Requirements.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db_prefix  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_write_config" class="anchor"></a>
####  write_config() : boolean

```
 write_config(array  $system = array()) : boolean
```

**Summary**

Write htaccess file based on the configuration

**Details:**
* File: [classes\PHPFusion\Installer\Requirements.php](../files/classes.PHPFusion.Installer.Requirements.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $system  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |


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
