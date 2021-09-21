# Multilingual Content

---

Almost all Multilingual contents are instanced in PHPFusion 9.
This means that you will usually need to be on the selected Language in order to view and to add Multilingual content.

This is however not without exception, our Multilingual support, and it's features are highly configurable.
Panels and Custom Pages have options to be displayed under any given Language.

In Panels, you are able to exclude or include all individual Panels for each enabled Language. The same arrayed method is enabled in Custom Pages as well.

Other sections have something we call Multilanguage Tables.

The Multilanguage Tables control if you want to include or exclude a certain section for Multilingual content.
You can for example untick Shoutbox from Administration -> Settings -> Language Settings : Tables with multilanguage content. By doing so all Shouts will be displayed under all installed Languages.

All Infusions that are created can have a line with its unique identifier that automatically adds a setting to the Multilanguage Tables when you install it.
Once the setting is available you can toggle it globally by excluding or including the Infusion from Multilingual content.

You will find the settings for the Multilanguage Tables under Administration -> Settings -> Language Settings.

To enable linking to and between multilingual content we created something that is called mlang hub (includes/core_mlang_hub_include.php).

Please note that this hub is only enabled for core components, it supports SEO and non SEO mode. Since everything is instanced per default you will for example not be able to read or see News under another language than your selected one.

Still you or your users might want people to be able to link to your multilingual sections and the content under any language, even when instanced.
The mlang hub is a solution that will solve this, the mlang hub will detect and set the correct language for the selected content if it is not set and not excluded from instances.

For example, If your site is English per default, and you have Chinese as secondary language, anyone who links to your Chinese language content will also read the site and the linked content in Chinese once they reach the site following a link to Chinese content.
