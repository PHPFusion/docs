# Coding Standards for Infusions v9

---

## infusion.php

The basic structure of infusion.php

```php
<?php
/*-------------------------------------------------------+
| PHPFusion Content Management System
| Copyright (C) PHP Fusion Inc
| https://phpfusion.com/
+--------------------------------------------------------+
| Filename: infusion.php
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
defined('IN_FUSION') || exit;

$locale = fusion_get_locale("", SHOUTBOX_LOCALE);

// Infusion general information
$inf_title = $locale['SB_title'];
$inf_description = $locale['SB_desc'];
$inf_version = "1.1";
$inf_developer = "PHPFusion Development Team";
$inf_email = "i";
$inf_weburl = "https://www.phpfusion.com";
$inf_folder = "shoutbox_panel";
$inf_image = "shouts.svg";

// Create tables
$inf_newtable[] = DB_SHOUTBOX." (
    shout_id MEDIUMINT(8) UNSIGNED NOT NULL AUTO_INCREMENT,
    shout_name VARCHAR(50) NOT NULL DEFAULT '',
    shout_message VARCHAR(200) NOT NULL DEFAULT '',
    shout_datestamp INT(10) UNSIGNED NOT NULL DEFAULT '0',
    shout_ip VARCHAR(45) NOT NULL DEFAULT '',
    shout_ip_type TINYINT(1) UNSIGNED NOT NULL DEFAULT '4',
    shout_hidden TINYINT(4) NOT NULL DEFAULT '0',
    shout_language VARCHAR(50) NOT NULL DEFAULT '".LANGUAGE."',
    PRIMARY KEY (shout_id),
    KEY shout_datestamp (shout_datestamp)
) ENGINE=MyISAM DEFAULT CHARSET=UTF8 COLLATE=utf8_unicode_ci";

// Insert panel
$inf_insertdbrow[] = DB_PANELS." (panel_name, panel_filename, panel_content, panel_side, panel_order, panel_type, panel_access, panel_display, panel_status, panel_url_list, panel_restriction, panel_languages) VALUES('".fusion_get_locale("SB_title", SHOUTBOX_LOCALE)."', '".$inf_folder."', '', '4', '3', 'file', '0', '1', '1', '', '3', '".fusion_get_settings('enabled_languages')."')";

// Insert settings
$settings = [
    'visible_shouts' => 5,
    'guest_shouts'   => 0,
    'hidden_shouts'  => 0
];

foreach ($settings as $name => $value) {
    $inf_insertdbrow[] = DB_SETTINGS_INF." (settings_name, settings_value, settings_inf) VALUES ('".$name."', '".$value."', '".$inf_folder."')";
}
```

## Infuse insertations

```php
$inf_insertdbrow[] = DB_PANELS." (panel_name, panel_filename, panel_content, panel_side, panel_order, panel_type, panel_access, panel_display, panel_status, panel_url_list, panel_restriction, panel_languages) VALUES('".fusion_get_locale("SB_title", SHOUTBOX_LOCALE)."', '".$inf_folder."', '', '4', '3', 'file', '0', '1', '1', '', '3', '".fusion_get_settings('enabled_languages')."')";
// Insert settings
$settings = [
    'visible_shouts' => 5,
    'guest_shouts'   => 0,
    'hidden_shouts'  => 0
];

foreach ($settings as $name => $value) {
    $inf_insertdbrow[] = DB_SETTINGS_INF." (settings_name, settings_value, settings_inf) VALUES ('".$name."', '".$value."', '".$inf_folder."')";
}
```

## Defuse cleaning

```php
$inf_droptable[] = DB_SHOUTBOX;
$inf_deldbrow[] = DB_ADMIN." WHERE admin_rights='S'";
$inf_deldbrow[] = DB_PANELS." WHERE panel_filename='".$inf_folder."'";
$inf_deldbrow[] = DB_SETTINGS_INF." WHERE settings_inf='".$inf_folder."'";
$inf_deldbrow[] = DB_LANGUAGE_TABLES." WHERE mlt_rights='SB'";
```

## infusion_db.php

Usually the infusion_db.php file is used to define constants for database table names, which are used by the Infusion programmer in various files of the infusion. Its basic contents are like

```php
<?php
/*-------------------------------------------------------+
| PHPFusion Content Management System
| Copyright (C) PHP Fusion Inc
| https://phpfusion.com/
+--------------------------------------------------------+
| Filename: infusion_db.php
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
defined('IN_FUSION') || exit;

PHPFusion\Admins::getInstance()->setAdminPageIcons("S", "<i class='admin-ico fa fa-fw fa-commenting'></i>");

const DB_SHOUTBOX = DB_PREFIX."shoutbox";

// Added Shoutbox Locale Constant
if (!defined("SHOUTBOX_LOCALE")) {
    if (file_exists(INFUSIONS."shoutbox_panel/locale/".LOCALESET."shoutbox.php")) {
        define("SHOUTBOX_LOCALE", INFUSIONS."shoutbox_panel/locale/".LOCALESET."shoutbox.php");
    } else {
        define("SHOUTBOX_LOCALE", INFUSIONS."shoutbox_panel/locale/English/shoutbox.php");
    }
}
```

When you are creating your own Infusion, you may need your own tables in the database.

Here you will get to know, how to create tables, drop tables, insert rows, delete rows in your own custom tables.

## Creating Tables

You can create tables in the Database in the infusion.php file as:

```php
$inf_newtable[] = DB_SHOUTBOX." (
    shout_id MEDIUMINT(8) UNSIGNED NOT NULL AUTO_INCREMENT,
    shout_name VARCHAR(50) NOT NULL DEFAULT '',
    shout_message VARCHAR(200) NOT NULL DEFAULT '',
    shout_datestamp INT(10) UNSIGNED NOT NULL DEFAULT '0',
    shout_ip VARCHAR(45) NOT NULL DEFAULT '',
    shout_ip_type TINYINT(1) UNSIGNED NOT NULL DEFAULT '4',
    shout_hidden TINYINT(4) NOT NULL DEFAULT '0',
    shout_language VARCHAR(50) NOT NULL DEFAULT '".LANGUAGE."',
    PRIMARY KEY (shout_id),
    KEY shout_datestamp (shout_datestamp)
) ENGINE=MyISAM DEFAULT CHARSET=UTF8 COLLATE=utf8_unicode_ci";
```

Here, DB_SHOUTBOX is the constant which holds the table name in the database, say, table_prefix_shoutbox. And the information like shout_id, shout_name etc. are the fields and its attributes in the table.

These tables are created in the database, when infusing the infusion.

## Inserting Rows in Tables

If you want to insert any Rows into some tables at the time Infusion is being infused, you can do it easily. It can be specified as:

```php
$inf_insertdbrow[] = DB_TABLE." (field1, field2, field3) VALUES('some value','some value', 'some value')";
```

Here, DB_TABLE is the table name in database, in which you want to insert a row.
field1, field2 and field3 are the fields of the table, in which you are inserting some values.

## Dropping Tables & Rows

When you have created tables, so you must also specify the tables to be Dropped at the time of Defusing the infusion. It can be specified as: (Example)

```php
$inf_droptable[] = DB_SHOUTBOX;
$inf_deldbrow[] = DB_ADMIN." WHERE admin_rights='S'";
```

Here, DB_SHOUTBOX is the constant which holds the Table name in the Database, which is to be droped.

$inf_droptable[] represents that it is the 1st table you want to Drop.

So, if you want to drop more tables, then you have to create more variables like:

$inf_droptable[] = some_table_name.

$inf_deldbrow[] = some row within a table.

and so on…

## Adding Admin Page Link & Access Rights of Infusion

If you want to insert an Admin page link to the admin panel, you can do it as: 

```php
$inf_adminpanel[] = [
    "title"    => $locale['SB_admin1'],
    "image"    => $inf_image,
    "panel"    => "shoutbox_admin.php",
    "rights"   => "S",
    "page"     => 5,
    "language" => LANGUAGE
];
```

Here, $inf_adminpanel[] is an array containing title, image, panel, rights, page and language.
- title is the text tile, which is to be given to the admin page link in admin panel.
- image is the image file name of the admin page link in admin panel, which exists in the directory administration/images/.
- panel is the admin page filename of the infusion, say myinfusion_admin.php.
- rights contain the short code for admin rights(e.g. SB for ShoutBox). It must not be more than 4 characters.
- page determines in which admin (1-5) section infusion will be displayed
- language is infusion language

## Adding Site links and Multilingual control tables to your infusion

If your Infusion have a multilanguage table you will want to populate the System Settings Multilanguage Table toggler with it like

```php
$inf_mlt[] = [
    "title"  => $inf_title,
    "rights" => "SB"
];
```

Here, the $locale['SB_title'] is the Multilanguage Table title for your Multilingual setting and the rights is SB for this, you can call this with ".multilang_table("SB")."

For an MySQL query in News simply add

```php
".(multilang_table("SB") ? "WHERE shout_language='".LANGUAGE."' AND" : "WHERE")."
```

If the Multilanguage table SB is not enabled the WHERE is triggered instead of language table check.

Here, we scan through all enabled languages in the locale folder and adds these to site links.

```php
$enabled_languages = makefilelist(LOCALE, '.|..', TRUE, 'folders');
if (!empty($enabled_languages)) {
    foreach ($enabled_languages as $language) {
        if (file_exists(INFUSIONS.'file/locale/'.$language.'/file.php')) {
            include INFUSIONS.'file/locale/'.$language.'/file.php';
        } else {
            include INFUSIONS.'file/locale/English/file.php';
        }

        $mlt_adminpanel[$language][] = [
            'rights'   => 'file',
            'image'    => $inf_image,
            'title'    => $locale['file_title'],
            'panel'    => 'admin.php',
            'page'     => 1,
            'language' => $language
        ];

        // Add
        $mlt_insertdbrow[$language][] = DB_SITE_LINKS." (link_name, link_url, link_visibility, link_position, link_window, link_order, link_status, link_language) VALUES ('".$locale['file_title']."', 'infusions/file/file.php', '0', '2', '0', '2', '1', '".$language."')";
        $mlt_insertdbrow[$language][] = DB_SITE_LINKS." (link_name, link_url, link_visibility, link_position, link_window, link_order, link_status, link_language) VALUES ('".$locale['file_submit']."', 'submit.php?stype=w', ".USER_LEVEL_MEMBER.", '1', '0', '27', '1', '".$language."')";

        // Delete
        $mlt_deldbrow[$language][] = DB_SITE_LINKS." WHERE link_url='infusions/file/file.php' AND link_language='".$language."'";
        $mlt_deldbrow[$language][] = DB_SITE_LINKS." WHERE link_url='submit.php?stype=w' AND link_language='".$language."'";
        $mlt_deldbrow[$language][] = DB_file_CATS." WHERE file_cat_language='".$language."'";
        $mlt_deldbrow[$language][] = DB_ADMIN." WHERE admin_rights='file' AND admin_language='".$language."'";
    }
} else {
    $inf_adminpanel[] = [
        'rights'   => 'file',
        'image'    => $inf_image,
        'title'    => $locale['file_title'],
        'panel'    => 'admin.php',
        'page'     => 1,
        'language' => LANGUAGE
    ];

    $inf_insertdbrow[] = DB_SITE_LINKS." (link_name, link_url, link_visibility, link_position, link_window, link_order, link_status, link_language) VALUES ('".$locale['file_title']."', 'infusions/file/file.php', '0', '2', '0', '2', '1', '".LANGUAGE."')";
    $inf_insertdbrow[] = DB_SITE_LINKS." (link_name, link_url, link_visibility, link_position, link_window, link_order, link_status, link_language) VALUES ('".$locale['file_submit']."', 'submit.php?stype=w', ".USER_LEVEL_MEMBER.", '1', '0', '27', '1', '".LANGUAGE."')";
}
```

## Make use of SETTINGS_INF table whenever required

For the Site Settings, we use Settings Table (DB_SETTINGS) for storing/retrieving the settings related to the Core.

Similarly, For Settings of an infusion, there is a table provided which can be used by an Infusion developer to store/retrieve settings for an infusion.

The Table is Settings_INF table (DB_SETTINGS_INF), which has 3 fields: settings_name, settings_value, setting_inf.
- settings_name holds the name of the setting.
- settings_value holds the value of the corresponding settings_name.
- settings_inf holds the name of the infusion, for which the settings are stored. (e.g. shoutbox_panel)

## Localization Conventions

The Localization should be done in the familiar manner of PHPFusion, which makes it easy for a Developer as well as a Translator, to edit and alter them when required.

## Locales for Infusion related information

For the infusion related information like $inf_title & $inf_description, you may use locale familiar locales like $locale[inf_title'] & $locale[inf_desc'], where you will replace inf with familiar short code for your Infusion.

For Example: For ShoutBox infusion, we use the short code as SB. Thus, the locales are: $locale[SB_title'] & $locale[SB_desc']

## Naming of other Locales

The Locales should be named on basis of their usage. It makes them familiar and easy for use.

For Example: If we are using locales, one for user_name & other for password field, then we

should use the locales like: $locale[INF_username'] & $locale[INF_password']

Although, there is no harm in using numbered locales like $locale[INF_001'] etc. but it makes it more familiar.
