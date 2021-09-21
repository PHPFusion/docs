# format_word()

Returns a grammatical number word.

---

format_word( int $count, string $words [, array $options ] ) : string

## Parameters

$count (int) (Required)

$words (string) (Required) A string consisting of singular and plural delimited by a | symbol.

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| add_count | bool | true | Show number. |
| html | bool | false | Encase result with html_template, {%count%} {%result%} tags are used for placeholders for result replacements. |
| html_template | string | `<span class='fusion_count'>{%count%}</span> <span class='fusion_word'>{%result%}</span>` | HTML template to be used for output. |
| language | string | LANGUAGE | Current language. |

## Return Values

(string)

## Examples

```php
$array = [
    'Apple', 'Orange'
];
$count = count($array);

echo format_word($count, 'fruit|fruits');
// 2 fruits
```
