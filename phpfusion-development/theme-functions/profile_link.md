# profile_link()

User profile link.

---

profile_link( int $user_id, string $user_name, int $user_status [, string $class, bool $display_link ] ) : string

## Parameters

$user_id (int) (Required)

$user_name (string) (Required)

$user_status (int) (Required)

$class (string) (Optional) CSS class for the profile link. Default value: profile-link

$display_link (bool) (Optional) Allow clicking on the name, otherwise display only the name. Default value: true

## Return Values

(string) Link to the user's account along with the username correctly depending on the user's status.

## Examples

```php
$userdata = fusion_get_userdata();

echo profile_link($userdata['user_id'], $userdata['user_name'], $userdata['user_status']);
// <a href='profile.php?lookup=1' class='profile-link'>admin</a>
```
