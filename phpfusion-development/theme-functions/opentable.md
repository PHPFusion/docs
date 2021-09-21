# opentable()

Opens the main panel. The function is defined in the theme.php and is different from theme to theme.

---

opentable( string $title [, mixed $... ] ) : string

## Parameters

$title (string) (Required) Panel title.

$... (mixed) (optional) Zero or more parameters to be passed. You can add your own parameters to be used in the theme.

## Return Values

(string)

## Examples

```php
function opentable($title) {
    echo '<div class="panel panel-default">';

    echo '<div class="panel-heading">';
    echo '<h3>'.$title.'</h3>';
    echo '</div>';

    echo '<div class="panel-body">';
}

function closetable() {
    echo '</div>'; // .panel-body
    echo '</div>'; // .panel
}
```

```php
opentable('Title');
// Content goes here
closetable();
```
