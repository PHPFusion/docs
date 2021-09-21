# parse_text()

Parse BBCodes, smileys and any special characters to HTML string.

---

parse_text( string $value [, array $options ] ) : string

## Parameters

$value (string) (Required) String with unparsed text.

$options (array) (Optional) Array of options. Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| parse_smileys | bool | true | Smiley parsing. |
| parse_bbcode | bool | true | BBcode parsing. |
| decode | bool | true | Decode HTML entities. |
| default_image_folder | string | IMAGES | Image folder for parse_image_dir(). |
| add_line_breaks | bool | false | Allows nl2br(). |
| descript | bool | true | Sanitize text. |
| parse_usres | bool | true | Create user @tags. |

## Return Values

(string) Parsed string.

## Examples

```php
$value = 'Text :D [url]http://example.com/[/url]';

echo parse_text($value);
// Text <img class='smiley' src='images/smiley/grin.svg' alt='Grin'> <a href='http://example.com/'>http://example.com/</a>
```
