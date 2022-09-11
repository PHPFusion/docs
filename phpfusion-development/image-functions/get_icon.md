# get_icon()

Get the icon or `<i>` tag.

---

function get_icon(string $icon, string $class = "", string $tooltip = "") :string 

## Parameters

$icon (string) (Required) The name of the icon 

$class (string) (Optional) Additional class to be inserted into the i tag. Default value: ''

$tooltip (string) (Optional) The title of the icon. Default value: ''

## Return Values

(string) The glyph font icon contained `<i>` tag.

## Examples

```php
echo get_icon('search');
//<i class="fas fa-search"></i>
```

### Names of Icons in PHPFusion
This list is extensive but not exhaustive as it can be added with any names with set_icon() function.

During this list was made, the latest public icon release on font awesome package is FontAwesome 5 which can be found on https://fontawesome.com/

```private static $glyphicons = [
        'plus'              => 'fa-regular fa-plus',
        'minus'             => 'fa-regular fa-minus',
        'up'                => 'fa-regular fa-up',
        'down'              => 'fa-regular fa-down',
        'left'              => 'fa-regular fa-left',
        'right'             => 'fa-regular fa-right',
        'caret-up'          => 'fa-regular fa-caret-up',
        'caret-down'        => 'fa-regular fa-caret-down',
        'caret-left'        => 'fa-regular fa-caret-left',
        'caret-right'       => 'fa-regular fa-caret-right',
        'apply'             => 'fa-regular fa-check',
        'cancel'            => 'fa-regular fa-ban',
        'reset'             => 'fa-regular fa-rotate-left',
        'reply'             => 'fa-regular fa-reply',
        'forward'           => 'fa-regular fa-share-from-square',
        'first'             => 'fa-regular fa-angle-left',
        'last'              => 'fa-regular fa-angle-right',
        'next'              => 'fa-regular fa-angle-double-right',
        'previous'          => 'fa-regular fa-angle-double-left',
        'edit'              => 'fa-regular fa-edit',
        'delete'            => 'fa-regular fa-trash',
        'view'              => 'fa-regular fa-eye',
        'more'              => 'fa-regular fa-ellipsis-v',
        'filter'            => 'fa-regular fa-filters',
        'asc'               => 'fa-regular fa-sort-up',
        'desc'              => 'fa-regular fa-sort-down',
        'move'              => 'fa-regular fa-up-down-left-right',
        'maximize'          => 'fa-regular fa-maximize',
        'minimize'          => 'fa-regular fa-down-left-and-up-right-to-center',
        'user'              => 'fa-regular fa-user',
        'admin'             => 'fa-regular fa-user-secret',
        'user-profile'      => 'fa-regular id-badge',
        'user-groups'       => 'fa-regular fa-users-rectangle',
        'user-active'       => 'fa-regular fa-user-check',
        'user-joined'       => 'fa-regular fa-calendar-circle-user',
        'user-banned'       => 'fa-regular fa-user-xmark',
        'user-inactive'     => 'fa-regular fa-user-clock',
        'forum-post'        => 'fa-regular fa-messages',
        'forum-spam'        => 'fa-regular fa-message-xmark',
        'forum-sticky'      => 'fa-regular fa-message-arrow-up',
        'forum-question'    => 'fa-regular fa-message-question',
        'forum-answer'      => 'fa-regular fa-message-check',
        'forum-quote'       => 'fa-regular fa-message-quote',
        'forum-attachments' => 'fa-regular fa-message-image',
        'forum-warning'     => 'fa-regular fa-message-exclamation',
        'forum-reputation'  => 'fa-regular fa-hundred-points',
        'forum-upvoted'     => 'fa-regular fa-message-arrow-up',
        'forum-downvoted'   => 'fa-regular fa-message-arrow-down',
        'vote'              => 'fa-regular fa-check-to-slot',
        'unvote'            => 'fa-regular fa-xmark-to-slot',
        'note'              => 'fa-regular fa-note-sticky',
        'auto-bot'          => 'fa-regular fa-message-bot',
        'comments'          => 'fa-regular fa-comments',
        'comment'           => 'fa-regular fa-comment',
        'poll'              => 'fa-regular fa-square-poll-vertical',
        'games'             => 'fa-regular fa-dice',
        'print'             => 'fa-regular fa-print',
        'items'             => 'fa-regular fa-box-heart',
        'security'          => 'fa-regular fa-shield-cross',
        'infusion'          => 'fa-regular fa-magnet',
        'collection'        => 'fa-regular fa-gift',
        'coins'             => 'fa-regular fa-sack',
        'location'          => 'fa-regular fa-location-dot',
        'code'              => 'fa-regular fa-brackets-curly',
        'success'           => 'fa-regular fa-badge-check',
        'warning'           => 'fa-regular fa-triangle-exclamation',
        'danger'            => 'fa-regular fa-light-emergency-on',
        'donation'          => 'fa-regular fa-hands-holding-dollar',
        'import'            => 'fa-regular fa-up-to-line',
        'export'            => 'fa-regular fa-down-from-line',
        'time'              => 'fa-regular fa-fa-clock',
        'duration'          => 'fa-regular fa-clock-rotate-left',
        'locked'            => 'fa-regular fa-lock',
        'unlocked'          => 'fa-regular fa-lock-open',
        'login'             => 'fa-regular fa-right-to-bracket',
        'logout'            => 'fa-regular fa-right-from-bracket',
        'tech-support'      => 'fa-regular fa-headset',
        'maintenance'       => 'fa-regular fa-helmet-safety',
        'site-links'        => 'fa-regular fa-sitemap',
        'bug'               => 'fa-regular fa-bug',
        'contact'           => 'fa-regular fa-square-phone',
        'covid'             => 'fa-regular fa-virus-covid',
    ];```

