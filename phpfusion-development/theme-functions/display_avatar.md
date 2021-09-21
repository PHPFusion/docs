# display_avatar()

Show user avatar.

---

display_avatar( array $userdata, string $size [, string $class, bool $link, string $img_class, string $custom_avatar ] ) : string

## Parameters

$userdata (array) (Required) User data with user_id, user_name , user_avatar, user_status

$size (string) (Required) A size for CSS max-width and max-height.

$class (string) (Optional) CSS class for `<a>` tag. Default value: ''

$link (bool) (Optional) Wrap image with `<a>` tag. Default value: true

$img_class (string) (Optional) CSS class for `<img>` tag. Default value: ''

$custom_avatar (string) (Optional) The path to own default avatar. Default value: ''

## Return Values

(string)

## Examples

```php
$userdata = fusion_get_userdata();
echo display_avatar($userdata, '40px');
```
