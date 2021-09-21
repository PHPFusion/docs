# Locales

All texts in a PHPFusion site can be located in files we call Locales, this gives the site owners and the site users the ability to change both the displayed Language and the Language of the content.

---

There are many Locales available for the Core and a lot of Addons have separate Locales for download.
You will find our Core Locales in the [Tranalations](https://www.php-fusion.co.uk/translations/) section.

Each Addon need to provide with their own Locales, these can usually be found either included in the Addon by the Author or submitted to the Addon from a user contribution.


To change or add to your sites Core Languages,you must first upload the requested Locale(s) to your respective Locale folder.
Each Infusion, Panel, Theme etc. have their own Locale folders. (Since v9.10 you can download locales direcly form Language Settings)


You can control the site's Main Language adn additional Languages from Administration -> Settings -> Language Settings and select desired locale in the Site locale droplist.

PHPFusion as well as properly formatted Addons will first search for your users Locale Setting and then for Site's Locale settings as default.
Once the settings have been read the system will try to verify if there is a respective Locale file in that Language.
If the system locates the asked Language file it will be loaded for display. If none is found, it will default to English.

This is our standard code for Locale control.

```php
// Check if a locale file is available that match the selected Locale.
If (file_exists(INFUSIONS.'your_panel/locale/'.LANGUAGE.'.php')) {
   // Load the Locale file matching selection.
   $locale_file = INFUSIONS.'your_panel/locale/'.LANGUAGE.'.php';
} else {
   // Load the default Locale file if the above checks fail.
   $locale_file = INFUSIONS.'your_panel/locale/English.php';
   
   $locale = fusion_get_locale('', $locale_file);
}
```
