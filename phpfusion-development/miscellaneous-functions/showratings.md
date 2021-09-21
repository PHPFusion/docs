# showratings()

Display a ratings form.

---

showratings( string $rating_type, int $rating_item_id, string $rating_link ) : string

## Parameters

$rating_type (string) (Required)

$rating_item_id (int) (Required) The item id you are rating.

$rating_link (string) (Required) The link for the page which the rating is on.

## Return Values

(string)

## Examples

```php
require_once INCLUDES.'ratings_include.php';

showratings('A', $data['article_id'], INFUSIONS.'articles/articles.php?article_id='.$data['article_id']);
```
