# social_media_links()

Return a list of social media sharing services where an url can be shared.

---

social_media_links( string $url [, array $options ] ) : string

## Parameters

$url (string) (Required) The URL to share.

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| class | string | '' | Link CSS class. |
| facebook | bool | true | Enable Facebook sharing. |
| twitter | bool | true | Enable Twitter sharing. |
| reddit | bool | true | Enable Reddit sharing. |
| vk | bool | true | Enable VK sharing. |
| whatsapp | bool | true | Enable Whatsapp sharing. |
| telegram | bool | true | Enable Telegram sharing. |
| linkedin | bool | true | Enable Linkedin sharing. |

## Return Values

(string)

## Examples

```php
echo social_media_links('http://example.com/');
```
