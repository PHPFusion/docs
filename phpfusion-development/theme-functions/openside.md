# openside()

Opens the side panel. The function is defined in the theme.php and is different from theme to theme.

---

openside( [ string $title, string $class, mixed $... ] ) : string

## Parameters

$title (string) (Optional) Panel title. Default value: null

$class (string) (Optional) CSS class. Default value: ''

$... (mixed) (Optional) Zero or more parameters to be passed. You can add your own parameters to be used in the theme.

## Return Values

(string)

## Examples

```php
function openside($title = NULL, $class = '') {
    echo '<div class="panel panel-default '.$class.'">';

    echo '<div class="panel-heading">';
    echo $title;
    echo '</div>';

    echo '<div class="panel-body">';
}

function closeside() {
    echo '</div>'; // .panel-body
    echo '</div>'; // .panel
}
```

```php
openside('Title');
// Content goes here
closeside();
```
