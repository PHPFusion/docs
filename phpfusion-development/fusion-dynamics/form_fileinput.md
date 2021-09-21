# form_fileinput()

Generates a file upload input. The Dynamics Form Fileinput initializes a Jquery based fileinput component wrapper and adds a preset file_sanitizer file validation and upload handling. The Fileinput is based on [Kartik Bootstrap Fileinput](http://plugins.krajee.com/file-input) plugin for Bootstrap, and is currently one of the more popular fileinput plugin there is available on opensource as it can handle an unprecendented customization configuration layer on a single fileinput widget.

---

form_fileinput( string $input_name [, string $label, string $input_value, array $options ] ) : string

## Parameters

$input_name (string) (Required) Name of the input, by default it's also used as the ID for the input.

$label (string) (Optional) Input label. Default value: ''

$input_value (string) (Optional) The value to be displayed. Default value: ''

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| ---  | ---  | ---  | ---  |
| input_id | string | $input_name |  |
| upload_path | string | IMAGES | The upload path for the file(s). |
| required | bool | false | Whether this field is required during form submission. |
| safemode | bool | false | Extra security settings such as strict type GD2 checks, and other validationduring upload. |
| deactivate | bool | false | Disable the input and set it as readonly. |
| preview_off | bool | false |  |
| type | string | text | Possible value: image, html, text, video, audio, flash, object, file |
| width | string | '' | Accepts px or % values. |
| label | string | $locale['browse'] |  |
| inline | bool | true |  |
| class | string | '' | The input container wrapper class. |
| tip | string | '' | Displays a tip by the label. |
| ext_tip | string | '' | Displays a tip at the bottom of the input. |
| error_text | string | $locale['error_input_file'] |  |
| btn_class | string | btn-default |  |
| icon | string | fa fa-upload |  |
| jsonurl | bool | false |  |
| dropzone | bool | false |  |
| valid_ext | string | .jpg,.png,.PNG,.JPG,.JPEG,.gif,.GIF,.bmp,.BMP |  |
| thumbnail | bool | false | Set to true to create primary thumbnail. |
| thumbnail_w | int | 300 | The width of the primary thumbnail. |
| thumbnail_h | int | 300 | The height of the primary thumbnail. |
| thumbnail_folder | string | '' | The path to the primary thumnail storage. |
| thumbnail_ratio | int | 0 | Keep original ratio or forced square dimension. Possible value: 0, 1 |
| thumbnail_suffix | string | _t1 | Adds a suffix to primary thumbnail filename. |
| thumbnail2 | bool | false | Set to true to create secondary thumbnail. |
| thumbnail2_w | int | 600 | The width of the secondary thumbnail. |
| thumbnail2_h | int | 400 | The height of the secondary thumbnail. |
| thumbnail2_suffix | string | _t2 | Adds a suffix to secondary thumbnail filename. |
| thumbnail2_ratio | int | 0 | Keep original ratio or forced square dimension. Possible value: 0, 1 |
| delete_original | bool | false | This is used to delete the uploaded file. It can be used along with thumbnail creation where you can set this parameter to true to keep only the thumbnail. |
| max_width | int | 1800 | Defines a maximum alloweable image width. Only takes effect if type isset to image. |
| max_height | int | 1600 | Defines a maximum alloweable image height. Only takes effect if type is set to image. |
| max_byte | int | 15728640 | Defines a maximum alloweable image size. Only takes effect if type is set to image. |
| max_count | int | 1 | Sets a minimum alloweable file selection count per instance. Declare a new max_count to 10 to allow user to select 10 files. |
| multiple | bool | false | Whether the current fileinput allows multiple files selection per instance. |
| template | string | classic | Customize HTML output of the widget. Possible value: classic, modern, thumbnail, avatar, custom |
| media | bool | false | Displays a file media browser selector to allow user to select files within the upload_path to pick on. |
| placeholder | string | '' | A placeholder for the field. |
| form_id | string | '' | The current `<form`> element id that this widget is placed in. |
| hide_upload | bool | true | Show or hide an upload file button when file has been selected. |
| hide_remove | bool | false | Show or hide an remove file button when file has been selected. |
| krajee_disabled | bool | false | Disables Kartik Bootstrap Jquery plugin and shows a normal browser fileinput instead. |
| replace_upload | bool | false | Change the upload name to a new unique name upon successful upload. |

## Return Values

(string)

## Examples

```php
echo form_fileinput('upload_field', 'Upload Field');
```
