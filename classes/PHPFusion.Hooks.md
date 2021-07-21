# [PHPFusion Docs](../home.md)

# Final Class: \PHPFusion\Hooks
### Namespace: [\PHPFusion](../namespaces/PHPFusion.md)
---
**Summary:**

Class Hooks
Core class for storing, removing and run hook functions.

---
### Constants
* No constants found
---
### Properties
* [private $hooks](../classes/PHPFusion.Hooks.md#property_hooks)
* [private $instances](../classes/PHPFusion.Hooks.md#property_instances)
* [private $output](../classes/PHPFusion.Hooks.md#property_output)
* [private $filter_name](../classes/PHPFusion.Hooks.md#property_filter_name)
* [private $hook_args](../classes/PHPFusion.Hooks.md#property_hook_args)
---
### Methods
* [public get_instance()](../classes/PHPFusion.Hooks.md#method_get_instance)
* [public add_hook()](../classes/PHPFusion.Hooks.md#method_add_hook)
* [public get_hook()](../classes/PHPFusion.Hooks.md#method_get_hook)
* [public remove_hook()](../classes/PHPFusion.Hooks.md#method_remove_hook)
* [public remove_all_hook()](../classes/PHPFusion.Hooks.md#method_remove_all_hook)
* [public apply_hook()](../classes/PHPFusion.Hooks.md#method_apply_hook)
* [public apply_hook_once()](../classes/PHPFusion.Hooks.md#method_apply_hook_once)
* [public repeat_current_hook()](../classes/PHPFusion.Hooks.md#method_repeat_current_hook)
* [public filter_hook()](../classes/PHPFusion.Hooks.md#method_filter_hook)
* [public filter_hook_once()](../classes/PHPFusion.Hooks.md#method_filter_hook_once)
* [public repeat_hook_once()](../classes/PHPFusion.Hooks.md#method_repeat_hook_once)
* [public apply_all_hook()](../classes/PHPFusion.Hooks.md#method_apply_all_hook)
* [private get_function_args()](../classes/PHPFusion.Hooks.md#method_get_function_args)
---
### Details
* File: [classes\PHPFusion\Hooks.php](../files/classes.PHPFusion.Hooks.md)
* Package: PHPFusion
* Class Hierarchy:
  * \PHPFusion\Hooks
---
## Properties
<a name="property_hooks"></a>
#### private $hooks : 
---
**Type:** 

**Details:**


<a name="property_instances"></a>
#### private $instances : 
---
**Type:** 

**Details:**


<a name="property_output"></a>
#### private $output : 
---
**Type:** 

**Details:**


<a name="property_filter_name"></a>
#### private $filter_name : 
---
**Type:** 

**Details:**


<a name="property_hook_args"></a>
#### private $hook_args : array
---
**Type:** array

**Details:**



---
## Methods
<a name="method_get_instance" class="anchor"></a>
#### public get_instance() : static

```
Static public get_instance(string  $key = &#039;default&#039;) : static
```

**Summary**

Get an instance by key

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** static


<a name="method_add_hook" class="anchor"></a>
#### public add_hook() : boolean

```
public add_hook(string  $filter_name, string  $function, integer  $que, array  $default_args, integer  $accepted_args) : boolean
```

**Summary**

Register a hook into the $instance

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |
| <code>integer</code> | $que  | Optional, values 1-10, where 1 runs first and 10 runs last. |
| <code>array</code> | $default_args  | Optional, the default state of parameter during adding hook. |
| <code>integer</code> | $accepted_args  | Optional, the limitation of the hook parameters the hook can accept. |

**Returns:** boolean


<a name="method_get_hook" class="anchor"></a>
#### public get_hook() : array

```
public get_hook(string  $filter_name, string  $function = &#039;&#039;) : array
```

**Summary**

Returns the hook by $filter_name and $function

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |

**Returns:** array


<a name="method_remove_hook" class="anchor"></a>
#### public remove_hook() : boolean

```
public remove_hook(string  $filter_name, string  $function, integer  $que) : boolean
```

**Summary**

Remove a specified hook from the $instance

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |
| <code>integer</code> | $que  |  |

**Returns:** boolean


<a name="method_remove_all_hook" class="anchor"></a>
#### public remove_all_hook() 

```
public remove_all_hook(boolean  $que = FALSE) 
```

**Summary**

Remove all hooks from the $instance

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $que  |  |




<a name="method_apply_hook" class="anchor"></a>
#### public apply_hook() 

```
public apply_hook(string  $filter_name) 
```

**Summary**

Run the hooks by $filter_name and $args parameters
There will be no output. If you need an output, use filter hook.

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \Exception |  |




<a name="method_apply_hook_once" class="anchor"></a>
#### public apply_hook_once() : mixed&amp;#124;string

```
public apply_hook_once(string  $filter_name) : mixed&amp;#124;string
```

**Summary**

Run the hook filter, can be used multiple times within a loop to get the parse.

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \Exception |  |

**Returns:** mixed&#124;string


<a name="method_repeat_current_hook" class="anchor"></a>
#### public repeat_current_hook() : mixed&amp;#124;string

```
public repeat_current_hook(string  $filter_name) : mixed&amp;#124;string
```

**Summary**

Run the hook filter, can be used multiple times within a loop to get the parse.

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \Exception |  |

**Returns:** mixed&#124;string


<a name="method_filter_hook" class="anchor"></a>
#### public filter_hook() : array

```
public filter_hook(string  $filter_name) : array
```

**Summary**

Run the hooks by $filter_name and $args parameters
This filter must only run once in application.

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |

**Returns:** array


<a name="method_filter_hook_once" class="anchor"></a>
#### public filter_hook_once() : string

```
public filter_hook_once(string  $filter_name) : string
```

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |

**Returns:** string


<a name="method_repeat_hook_once" class="anchor"></a>
#### public repeat_hook_once() : string

```
public repeat_hook_once(string  $filter_name) : string
```

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filter_name  |  |

**Returns:** string


<a name="method_apply_all_hook" class="anchor"></a>
#### public apply_all_hook() 

```
public apply_all_hook() 
```

**Summary**

Apply all hooks

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)




<a name="method_get_function_args" class="anchor"></a>
#### private get_function_args() : array

```
private get_function_args(mixed  $default_args) : array
```

**Details:**
* Inherited From: [\PHPFusion\Hooks](../classes/PHPFusion.Hooks.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $default_args  |  |

**Returns:** array



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
