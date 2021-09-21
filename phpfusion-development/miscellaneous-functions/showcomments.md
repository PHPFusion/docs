# showcomments()

Display a comments form.

---

showcomments( string $comment_type, string $comment_db, string $comment_col, int $comment_item_id, string $clink [, bool $ratings ] ): string

## Parameters

$comment_type (string) (Required)

$comment_db (string) (Required) The database table where the item you want to comment on resides in.

$comment_col (string) (Required) The field in the table which holds the id for the item you want to comment on.

$comment_item_id (int) (Required) The actual id to the item you are commenting on.

$clink (string) (Required) The actual id to the item you are commenting on.

$ratings (bool) (Optional) Display ratings. Default value: false

## Return Values

(string)

## Examples

```php
require_once INCLUDES.'comments_include.php';

showcomments('A', DB_ARTICLES, 'article_id', $data['article_id'], INFUSIONS.'articles/articles.php?article_id='.$data['article_id']);
```
