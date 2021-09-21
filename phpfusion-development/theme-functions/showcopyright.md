# showcopyright()

Show the PHPFusion copyright with a link to the official PHPFusion support site, and the AGPL license.

---

showcopyright( [ string $class, bool $nobreak ] ) : string

## Parameters

$class (string) (Optional) The "class" attribute of the link. Default value: ''

$nobreak (bool) (Optional) If true `<br>` tag will be removed between copyright and AGPL license. Default value: false

## Return Values

(string)

## Examples

```php
echo showcopyright();
// Powered by <a href='https://www.phpfusion.com'>PHPFusion</a> Copyright &copy; 2020 PHP Fusion Inc<br />Released as free software without warranties under <a href='https://www.gnu.org/licenses/agpl-3.0.html' target='_blank'>GNU Affero GPL</a> v3.
```
