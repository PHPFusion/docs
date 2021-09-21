# display_captcha()

Display captcha.

---

display_captcha( [, array $options ] ) : string

## Parameters

$options (array) (Optional) Default value: []

| Name | Type | Default | Description |
| :--- | :--- | :--- | :--- |
| captcha_id | string | captcha_* | ID for captcha itself |
| input_id | string | captcha_code_* | ID for captcha input |
| image_id | string | captcha_image_* | ID for captcha image |

## Return Values

(string)

## Examples

```php
if (isset($_POST['submit_form'])) {
    // your code

    if (iGUEST) {
        $_CAPTCHA_IS_VALID = FALSE;
        include INCLUDES.'captchas/'.$settings['captcha'].'/captcha_check.php';
        if (!$_CAPTCHA_IS_VALID) {
            fusion_stop();
        }
    }

    if (fusion_safe()) {
        // your code

        redirect(FUSION_SELF);
    }
}

echo openform('testform', 'post', FUSION_SELF);
echo form_text('text', 'Text');

if (iGUEST) {
    include INCLUDES.'captchas/'.$settings['captcha'].'/captcha_display.php';
    $captcha_settings = [
        'captcha_id' => 'captcha_testing',
        'input_id'   => 'captcha_code_testing',
        'image_id'   => 'captcha_image_testing'
    ];

    echo display_captcha($captcha_settings);
}

echo form_button('submit_form', 'Submit', 'submit_form');
echo closeform();
```
