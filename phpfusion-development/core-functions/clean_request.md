# clean_request()

Generate a clean request URI.

---

clean_request( [ mixed $request_addition, array $filter_array, bool $keep_filtered ] ) : string

## Parameters

$request_addition (mixed) (Optional) 'page=1&ref=2' or array('page' =>; 1, 'ref' =>; 2). Default value: ''

$filter_array (array) (Optional) array('aid', 'page', 'ref'). Default value: []

$keep_filtered (bool) (Optional) True to keep filter, false to remove filter from FUSION_REQUEST. Default value: true

## Return Values

(string) Request URI.

## Examples

```php
// Original URI http://example.com/test.php?test=123
echo clean_request();
// /test.php

// Original URI http://example.com/test.php?test=aaaa&this=123
echo clean_request('', ['test'], FALSE);
// /test.php?this=123
```
