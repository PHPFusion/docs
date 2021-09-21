# PHPFusion Coding Standards

---

## Validation of input data

PHPFusion Defender have form validation that assists you in validating, filtering, and prepping your data.

Even if that doesn’t work for your use, be sure to always validate and sanitize all input data.

If you expect a numeric string for an input variable, you can check for that with the isnum() function.

If you pass data with form posts or `$_GET`, you should always use the form_sanitizer() or stripinput() function to sanitize the posted data.

Please keep in mind that this includes not only `$_POST` and `$_GET` variables but also cookies, strings and basically all data that is not created directly by your own code.

## Safety first

Always validate data to ensure that it contains the correct chars, types, length, size, etc.

Always filter the data as if it were tainted.

PHPFusion provides quite a few functions and tips to assist you in this process.

## Code in English

All comments, variable names, function names, class names, strings etc. should always be in English.

## Index Files

Always have an empty index.php file in your directories when you do not use index.php as the standard opening file.

You must have an empty index.php in your images, js, css, templates, etc. folders as well.

## File Format

Files should be saved with Unicode - UTF-8 encoding.

The BOM should not be used. Unlike UTF-16 and UTF-32, there's no byte order indicating in a UTF-8 encoded file. The BOM can have a negative side effect in PHP of sending output, preventing the application from being able to set its own headers. Unix line endings should be used (LF).

## Line Breaks

Files must be saved with Unix line breaks.

Ensure that your text editor is configured to save files with Unix line breaks

## Limit Line Length

Our eyes are more comfortable when reading tall and narrow columns of text.

We consider it to be good practice avoiding writing horizontally long lines of code.

In general, all lines of code should not be longer than 80 chars.

## Whitespace in Files

No whitespace can precede the opening PHP tag or follow the closing PHP tag.

Output can be buffered, so whitespace in your files can cause output to begin before PHPFusion outputs its content, leading to errors and an inability to send proper headers.

## Short Open Tags

Always use full PHP opening tags, not all servers have `short_open_tag` enabled.

<span class="text-danger">INCORRECT</span>

```php
<? echo $foo; ?>

<?=$foo?>
```

<span class="text-success">CORRECT</span>

```php
<?php 
echo $foo; 
?>
 ```

## PHP Closing Tag

The PHP closing tag on a PHP document `?>` is optional to the PHP parser.

However, if used, any whitespace following the closing tag, whether introduced by the developer, user, or an FTP application, can cause unwanted output followed by PHP errors, or if the latter are suppressed, blank pages.

For this reason we want all PHP files to omit the PHP closing tag and end with a single empty line instead.

## File Naming

Class filenames should always start with an uppercase letter, while any other file name (configurations, views, generic scripts, etc.) should all be in lowercase.

Class file names should match the name of the class itself. For example, if you have a class named MyClass, then its filename should also be MyClass.php.

<span class="text-danger">INCORRECT</span>

someclass.php

someClass.php

SOMECLASS.php

Some_Class.php

Some_class.php

Someclass.php

<span class="text-success">CORRECT</span>

SomeClass.php

## Headers

Headers provide a description of the file, and it should usually include Copyright, Filename, Author, License.

Example of a standard header

```php
/*-------------------------------------------------------+
| PHPFusion Content Management System
| Copyright (C) PHP Fusion Inc
| https://phpfusion.com/
+--------------------------------------------------------+
| Filename: filename.php
| Author: Core Development Team
+--------------------------------------------------------+
| This program is released as free software under the
| Affero GPL license. You can redistribute it and/or
| modify it under the terms of this license which you
| can read by viewing the included agpl.txt or online
| at www.gnu.org/licenses/agpl.html. Removal of this
| copyright header is strictly prohibited without
| written permission from the original author(s).
+--------------------------------------------------------*/
```

## Modifying headers

When you write a custom new file, then you are the Author of the file:

```php
+--------------------------------------------------------+
| Filename: filename.php
| Author: Your Name (Username/Nickname)
+--------------------------------------------------------+
```

When you have modified someone's file quite a bit beyond a few fixes, you would qualify as a Co-Author and you can increment the header as follows,

```php
+--------------------------------------------------------+
| Filename: filename.php
| Author: Core Development Team
| Co-Author: Your Name (Username/Nickname)
+--------------------------------------------------------+
```

You are not allowed to alter the PHPFusion Copyright's or the License section unless you are a PFDN member that use EPAL

## Secure Includes

When you create files that are intended to work as an includes to the core, always add a check to prevent direct access to these files.

This also applies to panels, functions and similar. Files such as Locales, CSS, JS files etc. can be excluded from this standard.

Snippet to use:

```php
defined('IN_FUSION') || exit; // The code should be one line directly after the header
```

## Always use echo

Always make use of echo to print a text in the output.

<span class="text-danger">INCORRECT</span>

```php
print 'This is some text.';
```

<span class="text-success">CORRECT</span>

```php
echo 'This is some text.';
```

## HTML as lowercased

Your HTML must always be containing Lowercase characters.

Uppercase characters are not XHTML compatible.

<span class="text-danger">INCORRECT</span>

```php
echo '<STRONG>I Love PHPFusion.</STRONG>';
```

<span class="text-success">CORRECT</span>

```php
echo '<strong>I Love PHPFusion.</strong>';
```

## Control Structures

PHPFusion should not use alternative syntaxes for control structures.

Always avoid jumping in and out of in PHP.

Do not use PHP short tags.

Content should be echoed.

Statements should be opened and closed with curly braces.

<span class="text-danger">INCORRECT</span>

```php
// Does not use curly braces and keeps jumping in and out of PHP while PHP short tag is occasionally used.

<? if ($username == 'User 1'): ?>
<h3>Hi User 1</h3>
<?php elseif ($username == 'User 2'): ?>
<h3>Hi User 2</h3>
<? else: ?>
<h3>No matching users found</h3>
<?php endif; ?>
```

<span class="text-success">CORRECT</span>

```php
// Using curly braces and does not jump in and out of PHP, echos the content and not using PHP short tags.

<?php 
if ($username == 'User 1') {
   echo '<h3>Hi User 1</h3>';
} elseif ($username == 'User 2') {
   echo '<h3>Hi User 2</h3>';
} else {
   echo '<h3>No matching users found</h3>';
}
?>
```

## Indentation

PHPFusion use an indent style called Kernel style - 1TBS, Also known as the one true brace style.

Make sure that your editor does not automatically indent all codes with one tab level from start.

<span class="text-danger">INCORRECT</span>

```php
// Everything is tabbed out one level, curly brace is on a new line, overall, inconsistent tabbing and spacing.

   function foo($bar) 
   {
   if (x <0) {
    return $negative;
    } elseif (x>0) {
            return $positive;
    } else {
   return $unknown;
    }
   }
```

<span class="text-success">CORRECT</span>

```php
function foo($bar) {
    if (x < 0) {
        return $negative;
    } elseif (x > 0) {
        return $positive;
    } else {
        return $unknown;
    }
}
```

## Bracket and parenthesis spacing

Parenthesis and B\brackets should not use any additional spaces.

The exception is that a space should always follow PHP control structures that accept arguments with parenthesis such as declare, do-while, elseif, for, foreach, if, switch, while, to help distinguish these from functions and in order to increase code readability.

<span class="text-danger">INCORRECT</span>

```php
// Spaces around array key
$arr[ $foo ] = 'foo';
```

<span class="text-success">CORRECT</span>

```php
// No spaces around array key
$arr[$foo] = 'foo';
```

<span class="text-danger">INCORRECT</span>

```php
// Spaces around parenthesis in function declarations
function foo ( $bar ) {
}
```

<span class="text-success">CORRECT</span>

```php
// No spaces around parenthesis in function declarations
function foo($bar) {

}
```

<span class="text-danger">INCORRECT</span>

```php
// A single space in interior parenthesis
foreach( $result->result() as $data ) {}
```

<span class="text-success">CORRECT</span>

```php
// A single space following PHP control structures, but not in interior parenthesis
foreach ($result->result() as $data) {}
```

## One File per Class

Use separate files for each class, unless the classes are closely related.

## Class and Function Naming

Class functions should be named to clearly indicate their function, preferably including a verb.

Try to avoid overly long and verbose names and separate multiple words with underscores.

<span class="text-danger">INCORRECT</span>

```php
class megaclass {}
class Mega_class {}
```

<span class="text-success">CORRECT</span>

```php
class MegaClass {}
```

<span class="text-danger">INCORRECT</span>

```php
// Not descriptive and needs underscore separator
function fileproperties() {}

// Better, still missing underscore separator
function getfileproperties() {}

// Way to many words
function get_the_file_properties_from_the_file() {}
```

<span class="text-success">CORRECT</span>

```php
// Descriptive with clear underscore separators
function get_file_properties() {}
```

## Commenting

Comments help to describe the flow and intent of the code.

When the code is quite obvious, it is not productive to repeat it with a lot of comments.

If you comment on the code, you can simply combine it to a single line in most of the cases.

<span class="text-danger">INCORRECT</span>

```php
// Prevent any possible XSS attacks via $_GET.
// Check if we have a stripget($_GET) function request
if (stripget($_GET)) {
    // The request found a bad pattern, terminate the script
    die("Prevented a XSS attack through a GET variable!");
}
// End of function
```

<span class="text-success">CORRECT</span>

```php
// Prevent any possible XSS attacks via $_GET.
if (stripget($_GET)) {
    die("Prevented a XSS attack through a GET variable!");
}
```

DocBlock style commenting is something we should use preceding class, method, and property declarations, so they can be picked up by IDEs.

<span class="text-success">CORRECT</span>

```php
/**
 * ClassName
 *
 * @package    Package Name
 * @subpackage Subpackage
 * @category   Category
 * @author     Author Name
 * @link       http://example.com
 */
```

<span class="text-success">CORRECT</span>

```php
class ClassName {
    /**
     * Data for class manipulation
     *
     * @var array
     */
    private $data;

    /**
     * Encodes string for use in example
     *
     * @param string $example Input string
     *
     * @return string
     */
    function encodeExample($example) {
    }
}
```

## Variables

The guidelines for variable naming are very similar to those used for classes and functions.

Variables should contain only lowercase letters, use underscore separators.

The naming should be made in such manner that it is and indicator of their purpose and contents.

Very short, non-wordy variables should only be used as iterators in for() loops.

<span class="text-danger">INCORRECT</span>

```php
// Single letter variables should only be used in for() loops
$k = "foo";

// Contains uppercase letters
$Str

// Uses CamelCasing, and could be shortened without losing semantic meaning
$bufferedText

// Uses multiple words, needs underscore separator
$groupid

// Way too long
$name_of_last_city_used
```

<span class="text-success">CORRECT</span>

```php
// Correct for() looping with use of single letter variable
for ($k = 0; $k < 10; $k++)

// Lowercase letters
$str

// We get the idea with no CamelCase
$buffer

// Multiple words with underscore as separator
$group_id

// Quite clear what it does in a short version
$last_city
```

## Code Grouping

Most often, certain tasks require quite a few lines of code. It is a good idea to keep these tasks grouped within separate blocks of code. This is best achived by adding a break. By adding a comment at the beginning the blocks, you also emphasize the visual separation.

<span class="text-danger">INCORRECT</span>

```php
if (stripget($_GET)) {
   die("Prevented a XSS attack through a GET variable!");
}
dbconnect($db_host, $db_user, $db_pass, $db_name);
unset($db_host, $db_user, $db_pass);
```

<span class="text-success">CORRECT</span>

```php
// Prevent any possible XSS attacks via $_GET.
if (stripget($_GET)) {
   die("Prevented a XSS attack through a GET variable!");
}

// Establish mySQL database connection
dbconnect($db_host, $db_user, $db_pass, $db_name);
unset($db_host, $db_user, $db_pass);
```

## Constants

Constants follow the same guidelines as variables, except constants should always be fully uppercase.

Always use Core constants when appropriate, i.e. INFUSIONS, NEWS, BASEDIR, IMAGES, etc.

The naming should be made in such manner that it is and indicator of the purpose and contents.

Very short, non-wordy constants should not be used.

<span class="text-danger">INCORRECT</span>

```php
// Missing underscore separator and not fully uppercase
const newbasedir

// Do not use single letter constants
const N

// Not descriptive at all
const S_C_VER
```

<span class="text-success">CORRECT</span>

```php
const NEW_BASEDIR

const GOOD
```

`TRUE`, `FALSE` and `NULL` keywords should always be fully uppercase.

<span class="text-danger">INCORRECT</span>

```php
if ($foo == true)
$bar = false;
function foo($bar = null)
```

<span class="text-success">CORRECT</span>

```php
if ($foo == TRUE)
$bar = FALSE;
function foo($bar = NULL)
```

## Avoid Deep Nesting

With many nested levels the code is harder to read and follow, even with proper Indentation.

<span class="text-danger">INCORRECT</span>

```php
function do_stuff() {
    // Things to do
    if (is_writable($folder)) {
        if ($fp = fopen($file_path, 'w')) {
            if ($stuff = get_some_stuff()) {
                if (fwrite($fp, $stuff)) {
                    // Things to do
                } else {
                    return FALSE;
                }
            } else {
                return FALSE;
            }
        } else {
            return FALSE;
        }
    } else {
        return FALSE;
    }
}
```

<span class="text-success">CORRECT</span>

```php
function do_stuff() {
    // Things to do

    if (!is_writable($folder)) {
        return FALSE;
    }

    if (!$fp = fopen($file_path, 'w')) {
        return FALSE;
    }

    if (!$stuff = get_some_stuff()) {
        return FALSE;
    }

    if (fwrite($fp, $stuff)) {
        // Things to do
    } else {
        return FALSE;
    }
}
```

## Aligning Arrays

Arrays should be formatted with a space separating each element after the comma `,` and spaces around the `=>` key association operator if possible.

Note that if the line declaring an array spans longer than 80 characters, each element should be broken into its own line and indented one level

<span class="text-danger">INCORRECT</span>

```php
// No spacing
$my_array = array("apple"=>"red","banana"=>"yellow","watermelon"=>"green");

// Bad indentation and mixed breaks, inconsistent spacing.
$my_array = array(
 "apple"=> "red", "banana"=>"yellow",
 "watermelon" =>"green",
"Lemon"=> "yellow",
"Strawberry" => "red");
```

<span class="text-success">CORRECT</span>

```php
// Spacing as required
$my_array = array("apple" => "red", "banana" => "yellow", "watermelon" => "green");

// Good indentation, nice breaks, consistent spacing
$my_array = array(
    "apple"      => "red",
    "banana"     => "yellow",
    "watermelon" => "green",
    "Lemon"      => "yellow",
    "Strawberry" => "red"
);

// A short array syntax `[]` is also allowed
$my_array = [
    "apple"      => "red",
    "banana"     => "yellow",
    "watermelon" => "green",
    "Lemon"      => "yellow",
    "Strawberry" => "red"
];
```

## Logical Operators

Use of the `||` 'or' comparison operator is discouraged, as its clarity on some output devices is low (looking like the number 11, for instance).

`&&` is preferred over `AND` but either are acceptable, and a space should always precede and follow `!`.

<span class="text-danger">INCORRECT</span>

```php
if ($foo || $bar)

// Okay but not recommended for common syntax highlighting applications

if ($foo AND $bar)

if ($foo == FALSE)
```

<span class="text-success">CORRECT</span>

```php
if ($foo OR $bar)

// Best practise
if ($foo && $bar)

if (!$foo)

if (!is_array($foo))
```

## Comparing Return Values and Typecasting

Some PHP functions return `false` on failure, but may also have a valid return value of “” or `0`, which would evaluate to `false` in loose comparisons.

Be explicit by comparing the variable type when using these return values in conditionals to ensure the return value is indeed what you expect, and not a value that has an equivalent loose-type evaluation.

Use the same stringency in returning and checking your own variables. Use `===` and `!==` as necessary.

## Debugging Code

Do not leave debugging code in your submissions, even when commented out.

Things such as var_dump(), print_r(), die(), exit() should not be included in your code unless it serves a specific purpose other than debugging.

## SQL Queries

SQL keywords should always be capitalized, `SELECT`, `INSERT`, `UPDATE`, `WHERE`, `AS`, `JOIN`, `ON`, `IN`, etc.

Break up extra long queries into multiple lines for readability, make the break for each clause.

<span class="text-danger">INCORRECT</span>

```php
// Keywords are lowercase and query is on one line
$result = dbquery("select foo, bar, baz, foofoo, foobar as raboof, foobaz from exp_pre_email_addresses where foo != 'oof' and baz != 'zab' order by foobaz limit 5, 100");

// One very huge line
$result = dbquery("SELECT f.*, f2.forum_name AS forum_cat_name, t.thread_id, t.thread_lastpost, t.thread_lastpostid, t.thread_subject, u.user_id, u.user_name, u.user_status, u.user_avatar FROM ".DB_FORUMS." fLEFT JOIN ".DB_FORUMS." f2 ON f.forum_cat = f2.forum_id LEFT JOIN ".DB_FORUM_THREADS." t ON f.forum_lastpostid = t.thread_lastpostid LEFT JOIN ".DB_USERS." u ON f.forum_lastuser = u.user_id ".(multilang_table("FO") ? "WHERE f.forum_language='".LANGUAGE."' AND" : "WHERE")." ".groupaccess('f.forum_access')." AND f.forum_id='".intval($this->forum_info['forum_id'])."' OR f.forum_cat='".intval($this->forum_info['forum_id'])."' OR f.forum_branch='".intval($this->forum_info['forum_branch'])."' ORDER BY forum_cat ASC");
```

<span class="text-success">CORRECT</span>

```php
// Keywords are capitalized and the query is easily readable
$result = dbquery("SELECT foo, bar, baz, foofoo, foobar AS raboof, foobaz FROM exp_pre_email_addresses WHERE foo != 'oof' AND baz != 'zab' ORDER BY foobaz LIMIT 5, 100");

// Query have a new line at each new clause
$result = dbquery("SELECT f.*, f2.forum_name AS forum_cat_name,
    t.thread_id, t.thread_lastpost, t.thread_lastpostid, t.thread_subject,
    u.user_id, u.user_name, u.user_status, u.user_avatar
    FROM ".DB_FORUMS." f
    LEFT JOIN ".DB_FORUMS." f2 ON f.forum_cat = f2.forum_id
    LEFT JOIN ".DB_FORUM_THREADS." t ON f.forum_lastpostid = t.thread_lastpostid
    LEFT JOIN ".DB_USERS." u ON f.forum_lastuser = u.user_id
    ".(multilang_table("FO") ? "WHERE f.forum_language='".LANGUAGE."' AND" : "WHERE")." ".groupaccess('f.forum_access')."
    AND f.forum_id='".intval($this->forum_info['forum_id'])."'
    OR f.forum_cat='".intval($this->forum_info['forum_id'])."'
    OR f.forum_branch='".intval($this->forum_info['forum_branch'])."'
    ORDER BY forum_cat ASC
");
```
