# showsublinks()

Displays Site Links navigation bar.

---

showsublinks( [ string $sep, string $class, array $options ] ) : string

## Parameters

$sep (string) (Optional) Separator between links. Default value: ''

$class (string) (Optional) CSS class of the navbar. Default value: navbar-default

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| id | string | DefaultMenu | ID of the menu. |
| container | bool | false | Show menu in `<div class="container">..</div>`. |
| container_fluid | bool | false | Show menu in `<div class="container-fluid">..</div>`. |
| responsive | bool | true | Disable responsiveness. |
| navbar_class | string | navbar-default | Already pre filled with value from $class. |
| nav_class | string | nav navbar-nav primary | `<ul>` CSS class. |
| additional_nav_class | string | '' | CSS class of the secondary `<ul>` |
| item_class | string | '' | `<li>` CSS class. |
| locale | array | [] | Additional locales. |
| separator | string | '' | Already pre filled with value from $sep. |
| links_per_page | int | null | Links per page. |
| grouping | bool | false | It works together with links_per_page. If you set links_per_page = 3, other links will be grouped under Show More dropdown. |
| show_banner | bool | false |  |
| show_header | string|bool | false | Custom header. |
| custom_header | string | '' |  |
| language_switcher | bool | false | Language switcher. |
| searchbar | bool | false | Search bar. |
| search_icon | string | fa fa-search | Search button icon. |
| searchbar_btn_class | string | btn-primary | Search button class. |
| caret_icon | string | caret | Cater icon. |
| link_position | array | [2, 3] |  |
| html_pre_content | string | '' |  |
| html_content | string | '' |  |
| html_post_content | string | '' |  |

## Return Values

(string)

## Examples

```php
echo showsublinks();
```
