# checkusergroup()

Check if user is assigned to the specified user group(s) and has the required user level.

---

checkusergroup( int $group, int $user_level, string $user_groups [, string $delim ] ) : bool

## Parameters

$group (int) (Required) The group number(s) you want to check for the user.

$user_level (int) (Required) User level.

$user_groups (string) (Required) Assigned groups to the user.

$delim (string) (Optional) Delimiter. Default value: ,

## Return Values

(bool) True if the user has access.

## Examples

```php
$page_access = USER_LEVEL_MEMBER;
$userdata = fusion_get_userdata();

if (checkusergroup($page_access, $userdata['user_level'], $userdata['user_groups'])) {
    echo 'You have access to this section.';
}
```
