# fusion_get_inf_locale_path()

Performs the language file checks to get the correct locale file for the current user.

---

fusion_get_inf_locale_path( string $locale_file, string $locale_folder [, bool $localeset_folder, string $default_lang ] ) : string

## Parameters

$locale_file (string) (Required) Locale file name.

$locale_folder (string) (Required) Path to locale files.

$localeset_folder (bool) (Optional) True if the infusion has multiple locale files, typical solution was to store the files in a localeset folder /English. Default value: true

$default_lang (string) (Optional) Default value: English

## Return Values

(string)

## Examples

```php
$locale = fusion_get_locale('', fusion_get_inf_locale_path('articles.php', INFUSIONS.'articles/locale/'));
```
