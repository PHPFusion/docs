# [PHPFusion Docs](home.md)

# Namespace: \
### Namespaces
* [\Defender](namespaces/Defender.md)
* [\PHPFusion](namespaces/PHPFusion.md)
### Classes
| Name | Summary |
| ---- | ------- |
| [\Authenticate](classes/Authenticate.md) | Authenticate class for compatibility reason |
| [\Checkbox](classes/Checkbox.md) | Class Checkbox
Validates Checkbox Input |
| [\Contact](classes/Contact.md) | Class Number
Validates Number Input |
| [\Date](classes/Date.md) | Class Date
Validates Date Input |
| [\Defender](classes/Defender.md) | Class Defender |
| [\Dynamics](classes/Dynamics.md) | Class Dynamics |
| [\FusionTabs](classes/FusionTabs.md) |  |
| [\LostPassword](classes/LostPassword.md) | LostPassword class for compatibility reason |
| [\Number](classes/Number.md) | Class Number
Validates Number Input |
| [\PasswordAuth](classes/PasswordAuth.md) | PasswordAuth class for compatibility reason |
| [\SqlHandler](classes/SqlHandler.md) |  |
| [\Text](classes/Text.md) | Class Text
Validates Text Input |
| [\Upload](classes/Upload.md) | Class Upload
Handles file or image uploads validation |
| [\Uri](classes/Uri.md) | Class Uri
Validates URL Input |
| [\User](classes/User.md) | Class User
Validates User type Input |
| [\UserFields](classes/UserFields.md) | UserFields class for compatibility reason |
| [\UserFieldsInput](classes/UserFieldsInput.md) | UserFieldsInput class for compatibility reason |
### Constants
<a name="constant_$p_side[name]" class="anchor"></a>
###### $p_side[name]
```
$p_side[name] = $p_side['name'] === 'U_CENTER' ? $admin_mess : ''
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_ADMIN" class="anchor"></a>
###### ADMIN
```
ADMIN = BASEDIR . 'administration/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_ADMIN_THEMES" class="anchor"></a>
###### ADMIN_THEMES
```
ADMIN_THEMES = BASEDIR . 'themes/admin_themes/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_BASEDIR" class="anchor"></a>
###### BASEDIR
```
BASEDIR = strpos(fusion_get_config(), '/') === FALSE ? '' : dirname(fusion_get_config()) . '/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_CHECKBOX_SWITCH_CSS" class="anchor"></a>
###### CHECKBOX_SWITCH_CSS
```
CHECKBOX_SWITCH_CSS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_CLASSES" class="anchor"></a>
###### CLASSES
```
CLASSES = BASEDIR . 'includes/classes/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COLORBOX" class="anchor"></a>
###### COLORBOX
```
COLORBOX = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_ADMIN" class="anchor"></a>
###### COOKIE_ADMIN
```
COOKIE_ADMIN = COOKIE_PREFIX . "admin"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_DOMAIN" class="anchor"></a>
###### COOKIE_DOMAIN
```
COOKIE_DOMAIN = $settings['site_host'] != 'localhost' ? $fusion_domain : FALSE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_LASTVISIT" class="anchor"></a>
###### COOKIE_LASTVISIT
```
COOKIE_LASTVISIT = COOKIE_PREFIX . "lastvisit"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_PATH" class="anchor"></a>
###### COOKIE_PATH
```
COOKIE_PATH = $settings['site_path']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_PREFIX" class="anchor"></a>
###### COOKIE_PREFIX
```
COOKIE_PREFIX = self::$connection['COOKIE_PREFIX']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_PREFIX" class="anchor"></a>
###### COOKIE_PREFIX
```
COOKIE_PREFIX = self::$connection['cookie_prefix']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_USER" class="anchor"></a>
###### COOKIE_USER
```
COOKIE_USER = COOKIE_PREFIX . "user"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_COOKIE_VISITED" class="anchor"></a>
###### COOKIE_VISITED
```
COOKIE_VISITED = COOKIE_PREFIX . "visited"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DATEPICKER" class="anchor"></a>
###### DATEPICKER
```
DATEPICKER = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_ADMIN" class="anchor"></a>
###### DB_ADMIN
```
DB_ADMIN = DB_PREFIX . "admin"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_ADMIN_RESETLOG" class="anchor"></a>
###### DB_ADMIN_RESETLOG
```
DB_ADMIN_RESETLOG = DB_PREFIX . "admin_resetlog"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_BBCODES" class="anchor"></a>
###### DB_BBCODES
```
DB_BBCODES = DB_PREFIX . "bbcodes"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_BLACKLIST" class="anchor"></a>
###### DB_BLACKLIST
```
DB_BLACKLIST = DB_PREFIX . "blacklist"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_COMMENTS" class="anchor"></a>
###### DB_COMMENTS
```
DB_COMMENTS = DB_PREFIX . "comments"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_CUSTOM_PAGES" class="anchor"></a>
###### DB_CUSTOM_PAGES
```
DB_CUSTOM_PAGES = DB_PREFIX . "custom_pages"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_CUSTOM_PAGES_CONTENT" class="anchor"></a>
###### DB_CUSTOM_PAGES_CONTENT
```
DB_CUSTOM_PAGES_CONTENT = DB_PREFIX . "custom_pages_content"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_CUSTOM_PAGES_GRID" class="anchor"></a>
###### DB_CUSTOM_PAGES_GRID
```
DB_CUSTOM_PAGES_GRID = DB_PREFIX . "custom_pages_grid"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_EMAIL_TEMPLATES" class="anchor"></a>
###### DB_EMAIL_TEMPLATES
```
DB_EMAIL_TEMPLATES = DB_PREFIX . "email_templates"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_EMAIL_VERIFY" class="anchor"></a>
###### DB_EMAIL_VERIFY
```
DB_EMAIL_VERIFY = DB_PREFIX . "email_verify"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_ERRORS" class="anchor"></a>
###### DB_ERRORS
```
DB_ERRORS = DB_PREFIX . "errors"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_FLOOD_CONTROL" class="anchor"></a>
###### DB_FLOOD_CONTROL
```
DB_FLOOD_CONTROL = DB_PREFIX . "flood_control"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_HANDLERS" class="anchor"></a>
###### DB_HANDLERS
```
DB_HANDLERS = BASEDIR . 'includes/db_handlers/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_INFUSIONS" class="anchor"></a>
###### DB_INFUSIONS
```
DB_INFUSIONS = DB_PREFIX . "infusions"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_LANGUAGE_SESSIONS" class="anchor"></a>
###### DB_LANGUAGE_SESSIONS
```
DB_LANGUAGE_SESSIONS = DB_PREFIX . "language_sessions"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_LANGUAGE_TABLES" class="anchor"></a>
###### DB_LANGUAGE_TABLES
```
DB_LANGUAGE_TABLES = DB_PREFIX . "mlt_tables"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_MESSAGES" class="anchor"></a>
###### DB_MESSAGES
```
DB_MESSAGES = DB_PREFIX . "messages"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_NEW_USERS" class="anchor"></a>
###### DB_NEW_USERS
```
DB_NEW_USERS = DB_PREFIX . "new_users"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_ONLINE" class="anchor"></a>
###### DB_ONLINE
```
DB_ONLINE = DB_PREFIX . "online"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PANELS" class="anchor"></a>
###### DB_PANELS
```
DB_PANELS = DB_PREFIX . "panels"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PERMALINK_ALIAS" class="anchor"></a>
###### DB_PERMALINK_ALIAS
```
DB_PERMALINK_ALIAS = DB_PREFIX . "permalinks_alias"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PERMALINK_METHOD" class="anchor"></a>
###### DB_PERMALINK_METHOD
```
DB_PERMALINK_METHOD = DB_PREFIX . "permalinks_method"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PERMALINK_REWRITE" class="anchor"></a>
###### DB_PERMALINK_REWRITE
```
DB_PERMALINK_REWRITE = DB_PREFIX . "permalinks_rewrites"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PREFIX" class="anchor"></a>
###### DB_PREFIX
```
DB_PREFIX = self::$connection['db_prefix']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_PREFIX" class="anchor"></a>
###### DB_PREFIX
```
DB_PREFIX = self::$connection['DB_PREFIX']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_RATINGS" class="anchor"></a>
###### DB_RATINGS
```
DB_RATINGS = DB_PREFIX . "ratings"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SESSIONS" class="anchor"></a>
###### DB_SESSIONS
```
DB_SESSIONS = DB_PREFIX . "sessions"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SETTINGS" class="anchor"></a>
###### DB_SETTINGS
```
DB_SETTINGS = DB_PREFIX . "settings"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SETTINGS_INF" class="anchor"></a>
###### DB_SETTINGS_INF
```
DB_SETTINGS_INF = DB_PREFIX . "settings_inf"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SETTINGS_THEME" class="anchor"></a>
###### DB_SETTINGS_THEME
```
DB_SETTINGS_THEME = DB_PREFIX . "settings_theme"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SITE_LINKS" class="anchor"></a>
###### DB_SITE_LINKS
```
DB_SITE_LINKS = DB_PREFIX . "site_links"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SMILEYS" class="anchor"></a>
###### DB_SMILEYS
```
DB_SMILEYS = DB_PREFIX . "smileys"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SUBMISSIONS" class="anchor"></a>
###### DB_SUBMISSIONS
```
DB_SUBMISSIONS = DB_PREFIX . "submissions"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_SUSPENDS" class="anchor"></a>
###### DB_SUSPENDS
```
DB_SUSPENDS = DB_PREFIX . "suspends"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_THEME" class="anchor"></a>
###### DB_THEME
```
DB_THEME = DB_PREFIX . "theme"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_USER_FIELD_CATS" class="anchor"></a>
###### DB_USER_FIELD_CATS
```
DB_USER_FIELD_CATS = DB_PREFIX . "user_field_cats"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_USER_FIELDS" class="anchor"></a>
###### DB_USER_FIELDS
```
DB_USER_FIELDS = DB_PREFIX . "user_fields"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_USER_GROUPS" class="anchor"></a>
###### DB_USER_GROUPS
```
DB_USER_GROUPS = DB_PREFIX . "user_groups"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_USER_LOG" class="anchor"></a>
###### DB_USER_LOG
```
DB_USER_LOG = DB_PREFIX . "user_log"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DB_USERS" class="anchor"></a>
###### DB_USERS
```
DB_USERS = DB_PREFIX . "users"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DEVMODE" class="anchor"></a>
###### DEVMODE
```
DEVMODE = 1
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_DYNAMICS" class="anchor"></a>
###### DYNAMICS
```
DYNAMICS = BASEDIR . 'includes/dynamics/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FORM_FILEINPUT" class="anchor"></a>
###### FORM_FILEINPUT
```
FORM_FILEINPUT = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_ADMIN_HEADER" class="anchor"></a>
###### FUSION_ADMIN_HEADER
```
FUSION_ADMIN_HEADER = TEMPLATES . 'admin_header.php'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_DATATABLES" class="anchor"></a>
###### FUSION_DATATABLES
```
FUSION_DATATABLES = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_FOOTER" class="anchor"></a>
###### FUSION_FOOTER
```
FUSION_FOOTER = TEMPLATES . 'footer.php'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_HEADER" class="anchor"></a>
###### FUSION_HEADER
```
FUSION_HEADER = TEMPLATES . 'header.php'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_IP" class="anchor"></a>
###### FUSION_IP
```
FUSION_IP = $_SERVER['REMOTE_ADDR']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_NULL" class="anchor"></a>
###### FUSION_NULL
```
FUSION_NULL = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_QUERY" class="anchor"></a>
###### FUSION_QUERY
```
FUSION_QUERY = isset($_SERVER['QUERY_STRING']) ? $_SERVER['QUERY_STRING'] : ""
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_REQUEST" class="anchor"></a>
###### FUSION_REQUEST
```
FUSION_REQUEST = isset($_SERVER['REQUEST_URI']) && $_SERVER['REQUEST_URI'] != "" ? $_SERVER['REQUEST_URI'] : $_SERVER['SCRIPT_NAME']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_ROOT" class="anchor"></a>
###### FUSION_ROOT
```
FUSION_ROOT = ''
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_ROOT_DIR" class="anchor"></a>
###### FUSION_ROOT_DIR
```
FUSION_ROOT_DIR = dirname(__DIR__) . '/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_FUSION_SELF" class="anchor"></a>
###### FUSION_SELF
```
FUSION_SELF = basename($_SERVER['PHP_SELF'])
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_HOLDERJS" class="anchor"></a>
###### HOLDERJS
```
HOLDERJS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iADMIN" class="anchor"></a>
###### iADMIN
```
iADMIN = $userdata['user_level'] <= USER_LEVEL_ADMIN ? 1 : 0
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iGUEST" class="anchor"></a>
###### iGUEST
```
iGUEST = $userdata['user_level'] == USER_LEVEL_PUBLIC ? 1 : 0
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_IMAGES" class="anchor"></a>
###### IMAGES
```
IMAGES = BASEDIR . 'images/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iMEMBER" class="anchor"></a>
###### iMEMBER
```
iMEMBER = FALSE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iMEMBER" class="anchor"></a>
###### iMEMBER
```
iMEMBER = $userdata['user_level'] <= USER_LEVEL_MEMBER ? 1 : 0
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_IN_QUANTUM" class="anchor"></a>
###### IN_QUANTUM
```
IN_QUANTUM = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_INCLUDES" class="anchor"></a>
###### INCLUDES
```
INCLUDES = BASEDIR . 'includes/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_INFUSIONS" class="anchor"></a>
###### INFUSIONS
```
INFUSIONS = BASEDIR . 'infusions/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_INSTALLATION_STEP" class="anchor"></a>
###### INSTALLATION_STEP
```
INSTALLATION_STEP = $_SESSION['step']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iSUPERADMIN" class="anchor"></a>
###### iSUPERADMIN
```
iSUPERADMIN = $userdata['user_level'] == USER_LEVEL_SUPER_ADMIN ? 1 : 0
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iUSER" class="anchor"></a>
###### iUSER
```
iUSER = $userdata['user_level']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iUSER_GROUPS" class="anchor"></a>
###### iUSER_GROUPS
```
iUSER_GROUPS = substr($userdata['user_groups'], 1)
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_iUSER_RIGHTS" class="anchor"></a>
###### iUSER_RIGHTS
```
iUSER_RIGHTS = $userdata['user_rights']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_JS_COOKIES" class="anchor"></a>
###### JS_COOKIES
```
JS_COOKIES = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LANGUAGE" class="anchor"></a>
###### LANGUAGE
```
LANGUAGE = is_dir(LOCALE . self::$localeset) ? self::$localeset : 'English'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LANGUAGE" class="anchor"></a>
###### LANGUAGE
```
LANGUAGE = $settings['locale']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LANGUAGE" class="anchor"></a>
###### LANGUAGE
```
LANGUAGE = $lang
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LOCALE" class="anchor"></a>
###### LOCALE
```
LOCALE = BASEDIR . 'locale/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LOCALESET" class="anchor"></a>
###### LOCALESET
```
LOCALESET = LANGUAGE . "/"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LOCALESET" class="anchor"></a>
###### LOCALESET
```
LOCALESET = $settings['locale'] . "/"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_LOCALESET" class="anchor"></a>
###### LOCALESET
```
LOCALESET = $lang . '/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_no_debugger" class="anchor"></a>
###### no_debugger
```
no_debugger = 1
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_NO_DEBUGGER" class="anchor"></a>
###### NO_DEBUGGER
```
NO_DEBUGGER = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_NUMBERS_ONLY_JS" class="anchor"></a>
###### NUMBERS_ONLY_JS
```
NUMBERS_ONLY_JS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_PAGENAV" class="anchor"></a>
###### PAGENAV
```
PAGENAV = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_PLOCATION" class="anchor"></a>
###### PLOCATION
```
PLOCATION = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_PM_JS" class="anchor"></a>
###### PM_JS
```
PM_JS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_PRISMJS" class="anchor"></a>
###### PRISMJS
```
PRISMJS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_PWTOGGLE" class="anchor"></a>
###### PWTOGGLE
```
PWTOGGLE = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_QUANTUM_MULTILOCALE_FIELDS" class="anchor"></a>
###### QUANTUM_MULTILOCALE_FIELDS
```
QUANTUM_MULTILOCALE_FIELDS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_QUOTES_GPC" class="anchor"></a>
###### ~~QUOTES_GPC~~*This option has been removed from PHP ini.*

```
QUOTES_GPC = (bool) ini_get('magic_quotes_gpc')
```

**deprecated**

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_SECRET_KEY" class="anchor"></a>
###### SECRET_KEY
```
SECRET_KEY = self::createRandomPrefix(32)
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_SECRET_KEY" class="anchor"></a>
###### SECRET_KEY
```
SECRET_KEY = $key
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_SECRET_KEY" class="anchor"></a>
###### SECRET_KEY
```
SECRET_KEY = md5('temp_cache_key')
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_SECRET_KEY_SALT" class="anchor"></a>
###### SECRET_KEY_SALT
```
SECRET_KEY_SALT = self::createRandomPrefix(32)
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_START_TIME" class="anchor"></a>
###### START_TIME
```
START_TIME = microtime(TRUE)
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_STOP_REDIRECT" class="anchor"></a>
###### STOP_REDIRECT
```
STOP_REDIRECT = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_STOP_REDIRECT" class="anchor"></a>
###### STOP_REDIRECT
```
STOP_REDIRECT = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_TABLE_SORTER" class="anchor"></a>
###### TABLE_SORTER
```
TABLE_SORTER = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_TEL_ONLY_JS" class="anchor"></a>
###### TEL_ONLY_JS
```
TEL_ONLY_JS = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_TEMPLATES" class="anchor"></a>
###### TEMPLATES
```
TEMPLATES = BASEDIR . 'themes/templates/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_THEME" class="anchor"></a>
###### THEME
```
THEME = $dir->getPathname() . "/"
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_THEMES" class="anchor"></a>
###### THEMES
```
THEMES = BASEDIR . 'themes/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_TIME" class="anchor"></a>
###### ~~TIME~~*Unnecessary constant.*

```
TIME = time()
```

**deprecated**
use time()
| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_tinymce" class="anchor"></a>
###### tinymce
```
tinymce = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_IP" class="anchor"></a>
###### USER_IP
```
USER_IP = $_SERVER['REMOTE_ADDR']
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_IP" class="anchor"></a>
###### USER_IP
```
USER_IP = uncompressipv6(FUSION_IP)
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_IP_TYPE" class="anchor"></a>
###### USER_IP_TYPE
```
USER_IP_TYPE = 6
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_LEVEL_ADMIN" class="anchor"></a>
###### USER_LEVEL_ADMIN
```
USER_LEVEL_ADMIN = -102
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_LEVEL_MEMBER" class="anchor"></a>
###### USER_LEVEL_MEMBER
```
USER_LEVEL_MEMBER = -101
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_LEVEL_PUBLIC" class="anchor"></a>
###### USER_LEVEL_PUBLIC
```
USER_LEVEL_PUBLIC = 0
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USER_LEVEL_SUPER_ADMIN" class="anchor"></a>
###### USER_LEVEL_SUPER_ADMIN
```
USER_LEVEL_SUPER_ADMIN = -103
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_USERPOPOVER" class="anchor"></a>
###### USERPOPOVER
```
USERPOPOVER = TRUE
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

<a name="constant_WIDGETS" class="anchor"></a>
###### WIDGETS
```
WIDGETS = BASEDIR . 'widgets/'
```

| Tag | Version | Desc |
| --- | ------- | ---- |
| package |  | Default |

### Functions
<a name="method__get_states" class="anchor"></a>
####  _get_states() 

```
 _get_states() 
```

**Summary**

Get states

**Description**

Used by form_geo dynamic UI to query states.

**Details:**
* File: [api\states.php](files/api.states.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_breadcrumb" class="anchor"></a>
####  add_breadcrumb() 

```
 add_breadcrumb(array  $link = array()) 
```

**Summary**

Add a link to the breadcrumb

**Details:**
* File: [breadcrumbs.php](files/breadcrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $link  | Keys: link, title |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_handler" class="anchor"></a>
####  add_handler() 

```
 add_handler(callback  $callback) 
```

**Summary**

Add a new output handler function

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>callback</code> | $callback  | The name of a function or other callable object |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_css" class="anchor"></a>
####  add_to_css() 

```
 add_to_css(string  $tag = &quot;&quot;) 
```

**Summary**

Add css code to the output

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_footer" class="anchor"></a>
####  add_to_footer() 

```
 add_to_footer(string  $tag = &quot;&quot;) 
```

**Summary**

Add content to the footer

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_head" class="anchor"></a>
####  add_to_head() 

```
 add_to_head(string  $tag = &quot;&quot;) 
```

**Summary**

Add content to the html head

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_jquery" class="anchor"></a>
####  add_to_jquery() 

```
 add_to_jquery(string  $tag = &quot;&quot;) 
```

**Summary**

Add javascript source code to the output

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tag  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_meta" class="anchor"></a>
####  add_to_meta() 

```
 add_to_meta(string  $name, string  $addition = &quot;&quot;) 
```

**Summary**

Append something to a meta tag

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>string</code> | $addition  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_add_to_title" class="anchor"></a>
####  add_to_title() 

```
 add_to_title(string  $addition = &quot;&quot;) 
```

**Summary**

Append something to the title of the page

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $addition  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_addnotice" class="anchor"></a>
####  addnotice() 

```
 addnotice(string  $status, string  $value, string  $key = FUSION_SELF, boolean  $remove_after_access = TRUE) 
```

**Summary**

Adds a notice message to the group identified by the key provided

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $status  | The status of the message. |
| <code>string</code> | $value  | The message. |
| <code>string</code> | $key  | The key identifying a group holding notices, by default the page name in which the notice was set. |
| <code>boolean</code> | $remove_after_access  | Whether the notice should be automatically removed after it was displayed once,
                                    if set to false when getnotices() is called you have the option to keep the notice even after it was accesed. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_addslash" class="anchor"></a>
#### (deprecated) -  addslash() : string

```
 addslash(string  $text) : string
```

**Summary**

Add Slash Function, add correct number of slashes depending on quotes_gpc

**Deprecated**
Deprecateduse addslashes()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_alert" class="anchor"></a>
####  alert() : string

```
 alert(string  $title, array  $options = array()) : string
```

**Summary**

Creates an alert bar.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $title  | Text inside the alert. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_array_depth" class="anchor"></a>
####  array_depth() : integer

```
 array_depth(array  $array) : integer
```

**Summary**

Get maximum depth of a hierarchy tree.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  | Results from dbquery_tree(). |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_articlecat" class="anchor"></a>
#### (deprecated) -  articlecat() : string

```
 articlecat(  $info, string  $sep = &quot;&quot;, string  $class = &quot;&quot;) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code>string</code> | $sep  |  |
| <code>string</code> | $class  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_articleopts" class="anchor"></a>
#### (deprecated) -  articleopts() : string

```
 articleopts(  $info,   $sep) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code></code> | $sep  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_articleposter" class="anchor"></a>
#### (deprecated) -  articleposter() : string

```
 articleposter(  $info, string  $sep = &quot;&quot;, string  $class = &quot;&quot;) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code>string</code> | $sep  |  |
| <code>string</code> | $class  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_badge" class="anchor"></a>
####  badge() : string

```
 badge(string  $label, array  $options = array()) : string
```

**Summary**

Creates badge.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $label  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_bar_color" class="anchor"></a>
####  bar_color() 

```
 bar_color(  $num,   $reverse) 
```

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $num  |  |
| <code></code> | $reverse  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_blacklist" class="anchor"></a>
####  blacklist() : string

```
 blacklist(string  $field) : string
```

**Summary**

UF blacklist for SQL - same as groupaccess() but $field is the user_id column.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  | The name of the field |

**Returns:** string - SQL condition. It can return an empty condition if the user_blacklist field is not installed!

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_breadcrumb_page_arrays" class="anchor"></a>
####  breadcrumb_page_arrays() 

```
 breadcrumb_page_arrays(  $tree_index,   $tree_full,   $id_col,   $title_col,   $getname,   $id) 
```

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $tree_index  |  |
| <code></code> | $tree_full  |  |
| <code></code> | $id_col  |  |
| <code></code> | $title_col  |  |
| <code></code> | $getname  |  |
| <code></code> | $id  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cache_bbcode" class="anchor"></a>
####  cache_bbcode() : array

```
 cache_bbcode() : array
```

**Summary**

Cache of all installed BBCodes from the database.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array - Array of all BBCodes.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cache_groups" class="anchor"></a>
####  cache_groups() : array

```
 cache_groups() : array
```

**Summary**

Cache of all user groups from the database.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array - Array of all user groups.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cache_smileys" class="anchor"></a>
####  cache_smileys() : array

```
 cache_smileys() : array
```

**Summary**

Cache of all smileys from the database.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array - Array of all smileys.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_calculate_byte" class="anchor"></a>
####  calculate_byte() : integer

```
 calculate_byte(integer  $total_bit) : integer
```

**Summary**

Returns nearest data unit.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $total_bit  | Number of bytes. |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_calling_codes" class="anchor"></a>
####  calling_codes() : array&amp;#124;mixed&amp;#124;null

```
 calling_codes(null  $country_code = NULL) : array&amp;#124;mixed&amp;#124;null
```

**Details:**
* File: [dynamics\includes\form_contact.php](files/dynamics.includes.form_contact.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>null</code> | $country_code  |  |

**Returns:** array&#124;mixed&#124;null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_catFullPath" class="anchor"></a>
####  catFullPath() : array&amp;#124;boolean

```
 catFullPath(string  $cat_id, string  $cat_tbl, string  $col_id, string  $col_parent, string  $col_title) : array&amp;#124;boolean
```

**Details:**
* File: [breadcrumbs.php](files/breadcrumbs.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $cat_id  |  |
| <code>string</code> | $cat_tbl  |  |
| <code>string</code> | $col_id  |  |
| <code>string</code> | $col_parent  |  |
| <code>string</code> | $col_title  |  |

**Returns:** array&#124;boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdarray" class="anchor"></a>
####  cdarray() : array&amp;#124;null

```
 cdarray(mixed  $result) : array&amp;#124;null
```

**Summary**

Cached associative object array.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array&#124;null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdarraynum" class="anchor"></a>
####  cdarraynum() : array&amp;#124;mixed

```
 cdarraynum(mixed  $result) : array&amp;#124;mixed
```

**Summary**

Fetch one row as a numeric array

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array&#124;mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdflush" class="anchor"></a>
####  cdflush() 

```
 cdflush() 
```

**Summary**

Runs cache flush command.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdquery" class="anchor"></a>
####  cdquery() : false&amp;#124;integer&amp;#124;mixed

```
 cdquery(string  $key, string  $query, array  $parameters = array()) : false&amp;#124;integer&amp;#124;mixed
```

**Summary**

Cached query.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $query  |  |
| <code>array</code> | $parameters  |  |

**Returns:** false&#124;integer&#124;mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdquery_tree" class="anchor"></a>
####  cdquery_tree() : array

```
 cdquery_tree(string  $key, string  $db, string  $id_col, string  $cat_col, null  $filter = NULL, null  $query_replace = NULL) : array
```

**Summary**

Hierarchy ID to category output.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $db  | Table name |
| <code>string</code> | $id_col  | ID column |
| <code>string</code> | $cat_col  | Category column |
| <code>null</code> | $filter  | Conditions |
| <code>null</code> | $query_replace  | Replace the entire query |

**Returns:** array - Returns cat-id relationships

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdquery_tree_full" class="anchor"></a>
####  cdquery_tree_full() : array

```
 cdquery_tree_full(string  $key, string  $db, string  $id_col, string  $cat_col, null  $filter = NULL, null  $query_replace = NULL) : array
```

**Summary**

Hierarchy full data output.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>string</code> | $db  |  |
| <code>string</code> | $id_col  |  |
| <code>string</code> | $cat_col  |  |
| <code>null</code> | $filter  | replace conditional structure |
| <code>null</code> | $query_replace  | replace the entire query structure |

**Returns:** array - Returns cat-id relationships with full data

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdreset" class="anchor"></a>
####  cdreset() 

```
 cdreset(string  $key) 
```

**Summary**

Resets the cache and invalidates it.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdresult" class="anchor"></a>
####  cdresult() : mixed&amp;#124;string

```
 cdresult(mixed  $result, integer  $row) : mixed&amp;#124;string
```

**Summary**

Fetch the first column of a specific row

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |
| <code>integer</code> | $row  |  |

**Returns:** mixed&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cdrows" class="anchor"></a>
####  cdrows() : integer

```
 cdrows(mixed  $result) : integer
```

**Summary**

Cached number of rows.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_censorwords" class="anchor"></a>
####  censorwords() : string

```
 censorwords(string  $text) : string
```

**Summary**

Replace offensive words with the defined replacement word.

**Description**

The list of offensive words and the replacement word are both defined in the Security Settings.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | Text that should be censored. |

**Returns:** string - Censored text.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_check_admin_pass" class="anchor"></a>
####  check_admin_pass() : boolean

```
 check_admin_pass(string  $password) : boolean
```

**Summary**

Check if admin password matches userdata.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $password  | Password. |

**Returns:** boolean - True if the password matches the user's admin password or if the admin's cookie or session is set and is valid.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_check_get" class="anchor"></a>
####  check_get() : boolean

```
 check_get(  $key) : boolean
```

**Summary**

Isset GET

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $key  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_check_panel_status" class="anchor"></a>
####  check_panel_status() : boolean

```
 check_panel_status(string  $side) : boolean
```

**Summary**

Checks the panel status for given side.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $side  | Possible value: left, right, upper, aupper, lower, blower, user1, user2, user3, user4 |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_check_post" class="anchor"></a>
####  check_post() : boolean

```
 check_post(  $key) : boolean
```

**Summary**

Isset POST

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $key  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_checkgroup" class="anchor"></a>
####  checkgroup() : boolean

```
 checkgroup(integer  $group, string  $delim = &#039;,&#039;) : boolean
```

**Summary**

Check if user is assigned to the specified user group.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group  | The group number you want to check for the user. |
| <code>string</code> | $delim  | Delimiter. |

**Returns:** boolean - True if the user is in the group.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_checkrights" class="anchor"></a>
####  checkrights() : boolean

```
 checkrights(string  $rights) : boolean
```

**Summary**

Check if an Administrator has the correct rights assigned.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  | Rights you want to check for the administrator. |

**Returns:** boolean - True if the user is an Administrator with rights defined in $rights.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_checkusergroup" class="anchor"></a>
####  checkusergroup() : boolean

```
 checkusergroup(integer  $group, integer  $user_level, string  $user_groups, string  $delim = &#039;,&#039;) : boolean
```

**Summary**

Check if user is assigned to the specified user group and has the required user level.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group  | The group number you want to check for the user. |
| <code>integer</code> | $user_level  | User level. |
| <code>string</code> | $user_groups  | Assigned groups to the user. |
| <code>string</code> | $delim  | Delimiter. |

**Returns:** boolean - True if the user has access.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_clean_input_name" class="anchor"></a>
####  clean_input_name() : array&amp;#124;string

```
 clean_input_name(mixed  $value) : array&amp;#124;string
```

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $value  |  |

**Returns:** array&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_clean_input_value" class="anchor"></a>
####  clean_input_value() : array&amp;#124;string

```
 clean_input_value(  $value) : array&amp;#124;string
```

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |

**Returns:** array&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_clean_request" class="anchor"></a>
####  clean_request() : string

```
 clean_request(mixed  $request_addition = &#039;&#039;, array  $filter_array = array(), boolean  $keep_filtered = TRUE) : string
```

**Summary**

Generate a clean Request URI.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $request_addition  | 'page=1&ref=2' or array('page' => 1, 'ref' => 2) |
| <code>array</code> | $filter_array  | array('aid','page', ref') |
| <code>boolean</code> | $keep_filtered  | True to keep filter, false to remove filter from FUSION_REQUEST.
                               If remove is true, to remove everything and keep $requests_array and $request
                               addition. If remove is false, to keep everything else except $requests_array |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cleanurl" class="anchor"></a>
####  cleanurl() : string

```
 cleanurl(string  $url) : string
```

**Summary**

Clean the URL and prevents entities in server globals.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | URL. |

**Returns:** string - $url clean and ready for use XHTML strict and without any dangerous code.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closecollapse" class="anchor"></a>
####  closecollapse() : string

```
 closecollapse() : string
```

**Summary**

Close accordion.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closecollapsebody" class="anchor"></a>
####  closecollapsebody() : string

```
 closecollapsebody() : string
```

**Summary**

Close collapsing panel.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closeform" class="anchor"></a>
####  closeform() : string

```
 closeform() : string
```

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closemodal" class="anchor"></a>
####  closemodal() : string

```
 closemodal() : string
```

**Summary**

Close the modal.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closesidex" class="anchor"></a>
#### (deprecated) -  closesidex() 

```
 closesidex() 
```

**Deprecated**
Deprecateduse closeside()
**Details:**
* File: [deprecated.php](files/deprecated.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closetab" class="anchor"></a>
####  closetab() : string

```
 closetab(array  $options = array()) : string
```

**Summary**

Close tab.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_closetabbody" class="anchor"></a>
####  closetabbody() : string

```
 closetabbody() : string
```

**Summary**

Close tab body.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_colorbox" class="anchor"></a>
####  colorbox() : string

```
 colorbox(string  $img_path, string  $img_title, boolean  $responsive = TRUE, string  $class = &#039;&#039;, boolean  $as_text = FALSE) : string
```

**Summary**

Display image in colorbox.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $img_path  | The path to image. |
| <code>string</code> | $img_title  | Image title. |
| <code>boolean</code> | $responsive  | Add img-responsive class. |
| <code>string</code> | $class  | CSS class. |
| <code>boolean</code> | $as_text  | Show clickable text instead image. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_column_exists" class="anchor"></a>
####  column_exists() : boolean

```
 column_exists(string  $table, string  $column, boolean  $add_prefix = TRUE) : boolean
```

**Summary**

Determine whether column exists in a table.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table  | Table name. |
| <code>string</code> | $column  | Column name. |
| <code>boolean</code> | $add_prefix  | Add table prefix. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_combine_filter_query" class="anchor"></a>
####  combine_filter_query() 

```
 combine_filter_query(  $array) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $array  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_convert_to_bytes" class="anchor"></a>
####  convert_to_bytes() : integer

```
 convert_to_bytes(integer&amp;#124;string  $val) : integer
```

**Summary**

Convert to bytes.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer&#124;string</code> | $val  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cookie" class="anchor"></a>
####  cookie() 

```
 cookie(  $key,   $type = FILTER_DEFAULT) 
```

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $key  |  |
| <code></code> | $type  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_cookie_remove" class="anchor"></a>
####  cookie_remove() : array

```
 cookie_remove(string  $key) : array
```

**Summary**

Remove a $_COOKIE

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_copy_file" class="anchor"></a>
####  copy_file() : array

```
 copy_file(string  $source, string  $destination) : array
```

**Summary**

Copy a file from any source to any destination.

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source  | Copy file from URL. |
| <code>string</code> | $destination  | Destination folder. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_countdown" class="anchor"></a>
####  countdown() : string&amp;#124;null

```
 countdown(integer  $time) : string&amp;#124;null
```

**Summary**

Counts how many days remain until the specified date.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $time  | Timestamp. |

**Returns:** string&#124;null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_createsquarethumbnail" class="anchor"></a>
####  createsquarethumbnail() 

```
 createsquarethumbnail(string  $filetype, string  $origfile, string  $thumbfile, integer  $new_size) 
```

**Summary**

Create a square thumbnail image from an already uploaded image on your server.

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filetype  | This function only supports three filetypes: gif, jpeg, png, webp |
| <code>string</code> | $origfile  | Path to the orginal file you want to create a thumbnail of. |
| <code>string</code> | $thumbfile  | Path to the thumbnail file you want to create. |
| <code>integer</code> | $new_size  | Max size for thumbnail image. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_createthumbnail" class="anchor"></a>
####  createthumbnail() 

```
 createthumbnail(string  $filetype, string  $origfile, string  $thumbfile, integer  $new_w, integer  $new_h) 
```

**Summary**

Create a thumbnail image from an already uploaded image on your server.

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filetype  | This function only supports three filetypes: gif, jpeg, png, webp |
| <code>string</code> | $origfile  | Path to the orginal file you want to create a thumbnail of. |
| <code>string</code> | $thumbfile  | Path to the thumbnail file you want to create. |
| <code>integer</code> | $new_w  | Max width for thumbnail image. |
| <code>integer</code> | $new_h  | Max height for thumbnail image. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_custom_dbconnet" class="anchor"></a>
####  custom_dbconnet() : \PHPFusion\Database\AbstractDatabaseDriver

```
 custom_dbconnet(string  $db_host, string  $db_user, string  $db_pass, string  $db_name, integer  $db_port, string  $dbid) : \PHPFusion\Database\AbstractDatabaseDriver
```

**Summary**

Connect to the another database

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db_host  |  |
| <code>string</code> | $db_user  |  |
| <code>string</code> | $db_pass  |  |
| <code>string</code> | $db_name  |  |
| <code>integer</code> | $db_port  |  |
| <code>string</code> | $dbid  |  |

**Returns:** <a href="classes/PHPFusion.Database.AbstractDatabaseDriver.html">\PHPFusion\Database\AbstractDatabaseDriver</a>

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_days_current_month" class="anchor"></a>
####  days_current_month() : integer

```
 days_current_month() : integer
```

**Summary**

Days in the current month.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_db_exists" class="anchor"></a>
####  db_exists() : boolean

```
 db_exists(string  $table, boolean  $add_prefix = TRUE) : boolean
```

**Summary**

Check if a table exists.

**Description**

However you can pass the table name with or without prefix

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table  | The name of the table with or without prefix |
| <code>boolean</code> | $add_prefix  | Add table prefix. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbarray" class="anchor"></a>
####  dbarray() : array

```
 dbarray(mixed  $result) : array
```

**Summary**

Fetch one row as an associative array

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array - Associative array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbarraynum" class="anchor"></a>
####  dbarraynum() : array

```
 dbarraynum(mixed  $result) : array
```

**Summary**

Fetch one row as a numeric array

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** array - Numeric array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbconnect" class="anchor"></a>
####  dbconnect() : array

```
 dbconnect(string  $db_host, string  $db_user, string  $db_pass, string  $db_name, integer  $db_port = 3306, boolean  $halt_on_error = FALSE) : array
```

**Summary**

Connect to the database

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db_host  |  |
| <code>string</code> | $db_user  |  |
| <code>string</code> | $db_pass  |  |
| <code>string</code> | $db_name  |  |
| <code>integer</code> | $db_port  |  |
| <code>boolean</code> | $halt_on_error  | If it is TRUE, the script will halt in case of error |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbconnection" class="anchor"></a>
####  dbconnection() : \PHPFusion\Database\AbstractDatabaseDriver

```
 dbconnection() : \PHPFusion\Database\AbstractDatabaseDriver
```

**Summary**

Get the AbstractDatabase instance

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)

**Returns:** <a href="classes/PHPFusion.Database.AbstractDatabaseDriver.html">\PHPFusion\Database\AbstractDatabaseDriver</a>

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbcount" class="anchor"></a>
####  dbcount() : integer

```
 dbcount(string  $field, string  $table, string  $conditions = &quot;&quot;, array  $parameters = array()) : integer
```

**Summary**

Count the number of rows in a table filtered by conditions

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  | Parenthesized field name |
| <code>string</code> | $table  | Table name |
| <code>string</code> | $conditions  | Conditions after "where" |
| <code>array</code> | $parameters  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dblastid" class="anchor"></a>
####  dblastid() : integer

```
 dblastid() : integer
```

**Summary**

Get the last inserted auto increment id

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbnextid" class="anchor"></a>
####  dbnextid() : integer&amp;#124;false

```
 dbnextid(string  $table) : integer&amp;#124;false
```

**Summary**

Get the next auto_increment id of a table

**Description**

Try to avoid the use of it! [dblastid()](../namespaces/default.md#function_dblastid) after insert
is more secure way to get the id of an existing record than
get just a potential id.

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table  |  |

**Returns:** integer&#124;false

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbquery" class="anchor"></a>
####  dbquery() : mixed

```
 dbquery(string  $query, array  $parameters = array()) : mixed
```

**Summary**

Send a database query

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $query  | SQL |
| <code>array</code> | $parameters  |  |

**Returns:** mixed - The result of query or FALSE on error

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbquery_insert" class="anchor"></a>
####  dbquery_insert() : integer&amp;#124;false

```
 dbquery_insert(string  $table, array  $inputdata, string  $mode, array  $options = array()) : integer&amp;#124;false
```

**Summary**

MySQL row modifiers. Insert/Update/Delete.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table  | Table name. |
| <code>array</code> | $inputdata  | Input data. |
| <code>string</code> | $mode  | Possible value: save, update, delete |
| <code>array</code> | $options  |  |

**Returns:** integer&#124;false - If an error happens, it returns false.
                  Otherwise, if $mode is save and the primary key column is
                  incremented automatically, this function returns the last inserted id.
                  In other cases it always returns 0.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbquery_order" class="anchor"></a>
####  dbquery_order() : mixed

```
 dbquery_order(string  $dbname, integer  $current_order, string  $order_col, integer  $current_id, string  $id_col = NULL, integer  $current_category, string  $cat_col = NULL, boolean  $multilang = FALSE, string  $multilang_col = &#039;&#039;, string  $mode = &#039;update&#039;) : mixed
```

**Summary**

Table rows ordering.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $dbname  | Table name. |
| <code>integer</code> | $current_order  | Current order. |
| <code>string</code> | $order_col  | Column with order number. |
| <code>integer</code> | $current_id  | Current ID. ID is required only for update mode. |
| <code>string</code> | $id_col  | ID column. ID is required only for update mode. |
| <code>integer</code> | $current_category  | Current category. |
| <code>string</code> | $cat_col  | Category column. |
| <code>boolean</code> | $multilang  | Enable multilang. |
| <code>string</code> | $multilang_col  | Multilang column. |
| <code>string</code> | $mode  | Possible value: save, update, delete. |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbquery_tree" class="anchor"></a>
####  dbquery_tree() : array

```
 dbquery_tree(string  $db, string  $id_col, string  $cat_col, string  $filter = NULL, string  $query_replace = NULL) : array
```

**Summary**

Hierarchy ID to category output.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | Table name. |
| <code>string</code> | $id_col  | ID column. |
| <code>string</code> | $cat_col  | Category column. |
| <code>string</code> | $filter  | Replace conditional structure. |
| <code>string</code> | $query_replace  | Replace the entire query structure. |

**Returns:** array - Returns cat-id relationships.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbquery_tree_full" class="anchor"></a>
####  dbquery_tree_full() : array

```
 dbquery_tree_full(string  $db, string  $id_col, string  $cat_col, string  $filter = NULL, string  $query_replace = NULL) : array
```

**Summary**

Hierarchy full data output.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | Table name. |
| <code>string</code> | $id_col  | ID column. |
| <code>string</code> | $cat_col  | Category column. |
| <code>string</code> | $filter  | Replace conditional structure. |
| <code>string</code> | $query_replace  | Replace the entire query structure. |

**Returns:** array - Returns cat-id relationships with full data.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbresult" class="anchor"></a>
####  dbresult() : mixed

```
 dbresult(mixed  $result, integer  $row) : mixed
```

**Summary**

Fetch the first column of a specific row

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |
| <code>integer</code> | $row  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbrows" class="anchor"></a>
####  dbrows() : integer

```
 dbrows(mixed  $result) : integer
```

**Summary**

Count the number of affected rows by the given query

**Details:**
* File: [db_handlers\all_functions_include.php](files/db_handlers.all_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $result  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbtree" class="anchor"></a>
####  dbtree() : array

```
 dbtree(string  $db, string  $id_col, string  $cat_col, string  $cat_value = NULL, string  $filter = NULL) : array
```

**Summary**

Get hierarchy array with injected child key.

**Description**

This is a slower model to fetch hierarchy data than dbquery_tree_full();

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | Table name. |
| <code>string</code> | $id_col  | ID column. |
| <code>string</code> | $cat_col  | Category column. |
| <code>string</code> | $cat_value  | Category value. |
| <code>string</code> | $filter  | Replace conditional structure. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dbtree_index" class="anchor"></a>
####  dbtree_index() : array

```
 dbtree_index(string  $db, string  $id_col, string  $cat_col, string  $cat_value = NULL) : array
```

**Summary**

Lighter version of dbtree() with only id and child key.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | Table name. |
| <code>string</code> | $id_col  | ID column. |
| <code>string</code> | $cat_col  | Category column. |
| <code>string</code> | $cat_value  | Category value. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_define_site_language" class="anchor"></a>
####  define_site_language() 

```
 define_site_language(string  $lang) 
```

**Summary**

Define constants for site language.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $lang  | The name of the language. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_descript" class="anchor"></a>
####  descript() : string&amp;#124;array

```
 descript(string  $text, boolean  $strip_tags = TRUE, boolean  $strip_scripts = TRUE) : string&amp;#124;array
```

**Summary**

Sanitize text and remove a potentially dangerous HTML and JavaScript.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | String to be sanitized. |
| <code>boolean</code> | $strip_tags  | Removes potentially dangerous HTML tags. |
| <code>boolean</code> | $strip_scripts  | Removes <script> tags. |

**Returns:** string&#124;array - Sanitized and safe string.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_avatar" class="anchor"></a>
####  display_avatar() : string

```
 display_avatar(array  $userdata, string  $size, string  $class = &#039;&#039;, boolean  $link = TRUE, string  $img_class = &#039;&#039;, string  $custom_avatar = &#039;&#039;) : string
```

**Summary**

Show user avatar.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $userdata  | User data with user_id, user_name , user_avatar, user_status |
| <code>string</code> | $size  | A size for CSS max-width and max-height. |
| <code>string</code> | $class  | CSS class for <a> tag. |
| <code>boolean</code> | $link  | Wrap image with <a> tag. |
| <code>string</code> | $img_class  | CSS class for <img> tag. |
| <code>string</code> | $custom_avatar  | The path to own default avatar. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_bbcodes" class="anchor"></a>
####  display_bbcodes() : string

```
 display_bbcodes(string  $width, string  $textarea_name = &quot;message&quot;, string  $inputform_name = &quot;inputform&quot;, string  $selected = &quot;&quot;) : string
```

**Summary**

Display BBCode buttons for a given textarea.

**Details:**
* File: [bbcode_include.php](files/bbcode_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $width  | Width of the DIV which holds all the BBCode buttons. |
| <code>string</code> | $textarea_name  | The name of the textarea the BBCodes will be inserted to. |
| <code>string</code> | $inputform_name  | The name of the form the BBCodes will be inserted to. |
| <code>string</code> | $selected  | Show only certain BBCodes separated by |. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_comments" class="anchor"></a>
####  display_comments() : string

```
 display_comments(integer  $total_sum, string  $link = NULL, string  $class = NULL, integer  $mode = 1) : string
```

**Summary**

Display comments.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $total_sum  | Total number of comments. |
| <code>string</code> | $link  | Make item clickable. |
| <code>string</code> | $class  | CSS class for the link. |
| <code>integer</code> | $mode  | Show 2 out of 10 or 2/10 comments. Possible value: 1, 2. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_html" class="anchor"></a>
####  display_html() : string

```
 display_html(string  $formname, string  $textarea, boolean  $html = TRUE, boolean  $colors = FALSE, boolean  $images = FALSE, string  $folder = &quot;&quot;) : string
```

**Summary**

Display set of buttons.

**Details:**
* File: [html_buttons_include.php](files/html_buttons_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $formname  | The name of the form you are using the HTML buttons for. |
| <code>string</code> | $textarea  | The name of the textarea which html will be inserted to. |
| <code>boolean</code> | $html  | Setting this to true will display the HTML buttons. |
| <code>boolean</code> | $colors  | Setting this to true will display the HTML colors,. |
| <code>boolean</code> | $images  | Setting this to true will display the select field with images. |
| <code>string</code> | $folder  | If you have $images set to true, use this to define what image folder you want to get images from. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_parent_nodes" class="anchor"></a>
####  display_parent_nodes() : array

```
 display_parent_nodes(array  $data, string  $id_col, string  $cat_col, integer  $id) : array
```

**Summary**

Display parent nodes.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | Result from dbquery_tree(). |
| <code>string</code> | $id_col  | ID column. |
| <code>string</code> | $cat_col  | Category column. |
| <code>integer</code> | $id  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_ratings" class="anchor"></a>
####  display_ratings() : string

```
 display_ratings(integer  $total_sum, integer  $total_votes, string  $link = NULL, string  $class = NULL, integer  $mode = 1) : string
```

**Summary**

Display ratings.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $total_sum  | Total number of ratings. |
| <code>integer</code> | $total_votes  | Total number of votes. |
| <code>string</code> | $link  | Make item clickable. |
| <code>string</code> | $class  | CSS class for the link. |
| <code>integer</code> | $mode  | Show 2 out of 10 or 2/10 rating. Possible value: 1, 2. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_display_suspend_log" class="anchor"></a>
####  display_suspend_log() 

```
 display_suspend_log(integer  $user_id, string  $type = &quot;all&quot;, integer  $rowstart, integer  $limit) 
```

**Summary**

Display suspend log.

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |
| <code>string</code> | $type  |  |
| <code>integer</code> | $rowstart  |  |
| <code>integer</code> | $limit  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_displaysmileys" class="anchor"></a>
####  displaysmileys() : string

```
 displaysmileys(string  $textarea, string  $form = &quot;inputform&quot;) : string
```

**Summary**

Show smiley's button which will insert the smileys to the given textarea and form.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $textarea  | The id of the textarea |
| <code>string</code> | $form  | The form id in which the textarea is located. |

**Returns:** string - Option for users to insert smileys in a post by displaying the smiley's button.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_download_file" class="anchor"></a>
####  download_file() 

```
 download_file(string  $file) 
```

**Summary**

Download file from server.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $file  | The path to file. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_dropdown_select" class="anchor"></a>
####  dropdown_select() 

```
 dropdown_select(  $db,   $id_col,   $name_col,   $cat_col,   $index_values,   $filter = &#039;&#039;,   $query_replace = &#039;&#039;) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $db  |  |
| <code></code> | $id_col  |  |
| <code></code> | $name_col  |  |
| <code></code> | $cat_col  |  |
| <code></code> | $index_values  |  |
| <code></code> | $filter  |  |
| <code></code> | $query_replace  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_encode_code" class="anchor"></a>
####  encode_code() : string

```
 encode_code(string  $text) : string
```

**Summary**

Encode and format code inside <code> tag.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | String with code. |

**Returns:** string - Encoded and formatted code.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_environment" class="anchor"></a>
####  environment() : mixed

```
 environment(string  $key, integer  $type = FILTER_DEFAULT) : mixed
```

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>integer</code> | $type  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_exif" class="anchor"></a>
####  exif() : array&amp;#124;boolean

```
 exif(string  $image_path) : array&amp;#124;boolean
```

**Summary**

Get information about a specific image.

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $image_path  | Path to the image. |

**Returns:** array&#124;boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fetch_calling_codes" class="anchor"></a>
####  fetch_calling_codes() 

```
 fetch_calling_codes() 
```

**Summary**

Fetch calling codes

**Details:**
* File: [api\calling_codes.php](files/api.calling_codes.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fieldgenerator" class="anchor"></a>
####  fieldgenerator() : array

```
 fieldgenerator(string  $db) : array
```

**Summary**

MySQL show columns shorthand.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | Table name. |

**Returns:** array - Returns available columns in a table.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_file_sanitizer" class="anchor"></a>
####  file_sanitizer() : array

```
 file_sanitizer(string  $value, string  $default = &#039;&#039;, boolean  $input_name = FALSE) : array
```

**Summary**

File sanitize by input_name

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  | input_name |
| <code>string</code> | $default  |  |
| <code>boolean</code> | $input_name  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_file_uploaded" class="anchor"></a>
####  file_uploaded() : boolean

```
 file_uploaded(mixed  $key) : boolean
```

**Summary**

Checks if a file is uploaded during upload post event

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  | input name |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_filename_exists" class="anchor"></a>
####  filename_exists() : string

```
 filename_exists(string  $directory, string  $file = &#039;&#039;, array  $options = array()) : string
```

**Summary**

Checks if the file exists inside the folder.

**Description**

If not it will create a unique name for the file.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $directory  | The directory to check for the image. |
| <code>string</code> | $file  | The file in the directory you want to check. |
| <code>array</code> | $options  | dateformat - d,m,y, php date format constant, hash - false to remove hash string |

**Returns:** string - New unique filepath

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_filter_access_query" class="anchor"></a>
####  filter_access_query() 

```
 filter_access_query(  $group,   $field) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $group  |  |
| <code></code> | $field  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_filter_page_range" class="anchor"></a>
####  filter_page_range() 

```
 filter_page_range() 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_filter_query" class="anchor"></a>
####  filter_query() 

```
 filter_query(  $request_key,   $field_name) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $request_key  |  |
| <code></code> | $field_name  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_filter_show" class="anchor"></a>
####  filter_show() 

```
 filter_show(  $row_start_key = FALSE,   $items_per_page_key = FALSE) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $row_start_key  |  |
| <code></code> | $items_per_page_key  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_flatten_array" class="anchor"></a>
####  flatten_array() : array

```
 flatten_array(array  $array) : array
```

**Summary**

To flatten any multidimensional array.

**Description**

Best used to flatten any hierarchy array data.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  | Multidimensional array. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_flood_control" class="anchor"></a>
####  flood_control() : false&amp;#124;string

```
 flood_control(string  $field, string  $table, string  $where, false  $debug = FALSE) : false&amp;#124;string
```

**Summary**

Prevent users from flooding the system, typical spam bots and others.

**Description**

This function should be used whenever users have the ability to post to the database.

**Details:**
* File: [flood_include.php](files/flood_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  | The field in the table which holds the Unix timestamp. |
| <code>string</code> | $table  | The table you are flood controlling and where the UNIX timestamp field is located in. |
| <code>string</code> | $where  | The where statement to select the right rows and the right timestamp. This should either be a user_id or a user_id. |
| <code>false</code> | $debug  |  |

**Returns:** false&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_btngroup" class="anchor"></a>
####  form_btngroup() : string

```
 form_btngroup(  $input_name, string  $label,   $input_value, array  $options = array()) : string
```

**Summary**

Button Groups

**Details:**
* File: [dynamics\includes\form_buttons.php](files/dynamics.includes.form_buttons.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_button" class="anchor"></a>
####  form_button() 

```
 form_button(  $input_name,   $title,   $input_value, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_buttons.php](files/dynamics.includes.form_buttons.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $title  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_checkbox" class="anchor"></a>
####  form_checkbox() : string

```
 form_checkbox(  $input_name, string  $label = &#039;&#039;, string  $input_value = &#039;0&#039;, array  $options = array()) : string
```

**Details:**
* File: [dynamics\includes\form_checkbox.php](files/dynamics.includes.form_checkbox.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_colorpicker" class="anchor"></a>
####  form_colorpicker() 

```
 form_colorpicker(  $input_name,   $label = &#039;&#039;,   $input_value = &#039;&#039;, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_colorpicker.php](files/dynamics.includes.form_colorpicker.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_contact" class="anchor"></a>
####  form_contact() : string

```
 form_contact(  $input_name,   $label, string  $input_value = &quot;&quot;, array  $options = array()) : string
```

**Details:**
* File: [dynamics\includes\form_contact.php](files/dynamics.includes.form_contact.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_datepicker" class="anchor"></a>
####  form_datepicker() : string

```
 form_datepicker(  $input_name, string  $label = &#039;&#039;, string  $input_value = &#039;&#039;, array  $options = array()) : string
```

**Summary**

Input to save date using datepicker
Datetimepicker documentation - http://eonasdan.github.io/bootstrap-datetimepicker/Options/

**Details:**
* File: [dynamics\includes\form_datepicker.php](files/dynamics.includes.form_datepicker.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  | <ul>
               <li><strong>class</strong> (string): Empty string by default.
               The value of attribute class of the input.</li>
               <li><strong>date_format</strong> (string): dd-mm-yyyy by default.
               Date format for datepicker plugin.</li>
               <li><strong>deactivate</strong> (boolean): FALSE by default.
               You can pass TRUE and turn off the javascript datepicker plugin</li>
               <li><strong>error_text</strong> (string): empty string by default.
               An error message</li>
               <li><strong>fieldicon_off</strong> (boolean): FALSE by default.
               If TRUE, the calendar icon will be not displayed in the input.</li>
               <li><strong>inline</strong> (boolean): FALSE by default.
               TRUE if the input should be an inline element.</li>
               <li><strong>input_id</strong> (string): $input name by default.
               The value of attribute id of input.</li>
               <li><strong>required</strong> (boolean): FALSE by default</li>
               <li><strong>type</strong> (string): timestamp by default.
               Valid types:
               <ul>
               <li>date: The date will be saved as mysql date.</li>
               <li>timestamp: A timestamp will be saved as an integer</li>
               </ul>
               </li>
               <li><strong>week_start</strong> (int): 0 by default.
               An integer between 0 and 6. It is the same as
               the attribute weekStart of datepicker.</li>
               <li><strong>width</strong> (string): 250px by default.
               A valid value for CSS width</li>
               </ul>

Callback Usages !important
==========================
Configuration when type is 'timestamp'
Token used for $options['date_format_php'] is the <a href="http://php.net/manual/en/function.date.php">PHP token equivalent.</a>
Token used for $options['date_format_js'] must be formatted with <a href="http://momentjs.com/docs/#/displaying/">moment.js.</a>
Both token must match each other to parse the callback properly.
Example 1:
 "date_format_php" => "d-m-Y",
"date_format_js"  => "DD-MM-YYYY",

Example 2:
 'date_format_js'  => 'YYYY-M-DD',
'date_format_php' => 'Y-m-d',

Currently, only user birthdate in `entire project` uses date format.

Joining 2 datepickers (Start and End)
=======================================
In Start Datepicker, add $options['join_to_id'] with End Datepicker's input_id
In End Datepicker, add $options['join_from_id'] with Start Datepicker's input_id |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_fileinput" class="anchor"></a>
####  form_fileinput() : string

```
 form_fileinput(string  $input_name, string  $label = &#039;&#039;, boolean  $input_value = FALSE, array  $options = array()) : string
```

**Summary**

Generates a file upload input.

**Details:**
* File: [dynamics\includes\form_fileinput.php](files/dynamics.includes.form_fileinput.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  | Name of the input, by default it's also used as the ID for the input. |
| <code>string</code> | $label  | Input label. |
| <code>boolean</code> | $input_value  | The value to be displayed. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_geo" class="anchor"></a>
####  form_geo() : string

```
 form_geo(  $input_name, string  $label = &quot;&quot;, string  $input_value = &quot;&quot;, array  $options = array()) : string
```

**Details:**
* File: [dynamics\includes\form_geomap.php](files/dynamics.includes.form_geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_hidden" class="anchor"></a>
####  form_hidden() : string

```
 form_hidden(  $input_name, string  $label = &quot;&quot;, string  $input_value = &quot;&quot;, array  $options = array()) : string
```

**Details:**
* File: [dynamics\includes\form_hidden.php](files/dynamics.includes.form_hidden.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_location" class="anchor"></a>
####  form_location() 

```
 form_location(  $input_name,   $label = &#039;&#039;,   $input_value = FALSE, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_geomap.php](files/dynamics.includes.form_geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_modal" class="anchor"></a>
####  form_modal() 

```
 form_modal(  $modal_input,   $title,   $htmlcode = &quot;&quot;,   $array = FALSE) 
```

**Details:**
* File: [dynamics\includes\form_modal.php](files/dynamics.includes.form_modal.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $modal_input  |  |
| <code></code> | $title  |  |
| <code></code> | $htmlcode  |  |
| <code></code> | $array  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_name" class="anchor"></a>
####  form_name() 

```
 form_name(  $input_name,   $label = &quot;&quot;,   $input_value = FALSE, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_name.php](files/dynamics.includes.form_name.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_para" class="anchor"></a>
####  form_para() 

```
 form_para(  $title,   $id,   $class = &#039;underline&#039;, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_paragraph.php](files/dynamics.includes.form_paragraph.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $title  |  |
| <code></code> | $id  |  |
| <code></code> | $class  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_range" class="anchor"></a>
####  form_range() : string

```
 form_range(  $input_name, string  $label = &quot;&quot;, string  $input_value = &quot;&quot;, array  $options = array()) : string
```

**Details:**
* File: [dynamics\includes\form_range.php](files/dynamics.includes.form_range.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_sanitizer" class="anchor"></a>
####  form_sanitizer() : string&amp;#124;array

```
 form_sanitizer(string  $value, string  $default = &#039;&#039;, boolean  $input_name = FALSE, boolean  $is_multiLang = FALSE) : string&amp;#124;array
```

**Summary**

Verify and Sanitize Inputs

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |
| <code>string</code> | $default  |  |
| <code>boolean</code> | $input_name  |  |
| <code>boolean</code> | $is_multiLang  |  |

**Returns:** string&#124;array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_select" class="anchor"></a>
####  form_select() 

```
 form_select(  $input_name,   $label,   $input_value,   $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code></code> | $input_value  |  |
| <code></code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_form_select_build_optgroup" class="anchor"></a>
####  form_select_build_optgroup() 

```
 form_select_build_optgroup(  $array,   $input_value,   $options) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $array  |  |
| <code></code> | $input_value  |  |
| <code></code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_form_select_order" class="anchor"></a>
####  form_select_order() 

```
 form_select_order(  $title,   $input_name,   $input_id,   $option_array,   $input_value,   $chain_to_parent_id,   $array = FALSE) 
```

**Details:**
* File: [dynamics\includes\form_ordering.php](files/dynamics.includes.form_ordering.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $title  |  |
| <code></code> | $input_name  |  |
| <code></code> | $input_id  |  |
| <code></code> | $option_array  |  |
| <code></code> | $input_value  |  |
| <code></code> | $chain_to_parent_id  |  |
| <code></code> | $array  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_select_tree" class="anchor"></a>
####  form_select_tree() : string

```
 form_select_tree(  $input_name, string  $label, string  $input_value, array  $options,   $db,   $name_col,   $id_col,   $cat_col, boolean  $self_id = FALSE, boolean  $id = FALSE, boolean  $level = FALSE, boolean  $index = FALSE, boolean  $data = FALSE) : string
```

**Summary**

Select2 hierarchy
Returns a full hierarchy nested dropdown.

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>string</code> | $input_value  |  |
| <code>array</code> | $options  |  |
| <code></code> | $db  | - your db |
| <code></code> | $name_col  | - the option text to show |
| <code></code> | $id_col  | - unique id |
| <code></code> | $cat_col  | - parent id
                        ## The rest of the Params are used by the function itself -- no need to handle ## |
| <code>boolean</code> | $self_id  | - not required |
| <code>boolean</code> | $id  | - not required |
| <code>boolean</code> | $level  | - not required |
| <code>boolean</code> | $index  | - not required |
| <code>boolean</code> | $data  | - not required |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_form_text" class="anchor"></a>
####  form_text() : string

```
 form_text(string  $input_name, string  $label = &quot;&quot;, boolean  $input_value = &quot;&quot;, array  $options = array()) : string
```

**Summary**

Generates a text input.

**Details:**
* File: [dynamics\includes\form_text.php](files/dynamics.includes.form_text.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $input_name  | Name of the input, by default it's also used as the ID for the input. |
| <code>string</code> | $label  | Input label. |
| <code>boolean</code> | $input_value  | The value to be displayed. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_textarea" class="anchor"></a>
####  form_textarea() 

```
 form_textarea(  $input_name,   $label = &#039;&#039;,   $input_value = &#039;&#039;, array  $options = array()) 
```

**Details:**
* File: [dynamics\includes\form_textarea.php](files/dynamics.includes.form_textarea.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code></code> | $label  |  |
| <code></code> | $input_value  |  |
| <code>array</code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_form_user_select" class="anchor"></a>
####  form_user_select() : string

```
 form_user_select(  $input_name, string  $label = &quot;&quot;, boolean  $input_value = FALSE, array  $options = array()) : string
```

**Summary**

Selector for registered user

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $input_name  |  |
| <code>string</code> | $label  |  |
| <code>boolean</code> | $input_value  | - user id |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_format_code" class="anchor"></a>
####  format_code() : string

```
 format_code(string  $code) : string
```

**Summary**

Add correct amount of spaces and tabs inside code.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $code  | The code you want to format. |

**Returns:** string - Formatted code.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_format_float" class="anchor"></a>
####  format_float() : float

```
 format_float(string&amp;#124;integer  $value) : float
```

**Summary**

Converts any formatted number back to float numbers in PHP

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;integer</code> | $value  | Formatted number. |

**Returns:** float

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_format_num" class="anchor"></a>
####  format_num() : string

```
 format_num(integer  $value, integer  $decimals = NULL, string  $dec_point = &quot;.&quot;, string  $thousand_sep = &quot;,&quot;, boolean  $round = TRUE, boolean  $acryonym = TRUE) : string
```

**Summary**

Formats a number in a numeric acronym, and rounding.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $value  | Number to format. |
| <code>integer</code> | $decimals  | The number of decimals. |
| <code>string</code> | $dec_point  | Decimal point. |
| <code>string</code> | $thousand_sep  | Thousands separator. |
| <code>boolean</code> | $round  | Round number. |
| <code>boolean</code> | $acryonym  | Acronym. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_format_sentence" class="anchor"></a>
####  format_sentence() : string

```
 format_sentence(array  $words) : string
```

**Summary**

Returns a string of quantitative sentence from an array.

**Details:**
* File: [translate_include.php](files/translate_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $words  |  |

**Returns:** string - E.g. orange, banana and apples

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_format_word" class="anchor"></a>
####  format_word() : string

```
 format_word(integer  $count, string  $words, array  $options = array()) : string
```

**Summary**

Returns a grammatical number word.

**Details:**
* File: [translate_include.php](files/translate_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $count  | Number of items. |
| <code>string</code> | $words  | A string consisting of singular and plural delimited by a | symbol. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_formatcode" class="anchor"></a>
#### (deprecated) -  formatcode() : string

```
 formatcode(  $value) : string
```

**Deprecated**
Deprecateduse format_code()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_add_hook" class="anchor"></a>
####  fusion_add_hook() : boolean

```
 fusion_add_hook(string  $name, string  $function, integer  $que = 10, array  $default_args = array(), integer  $accepted_args = 1) : boolean
```

**Summary**

Add a hook.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |
| <code>integer</code> | $que  | Optional, values 1-10, where 1 runs first and 10 runs last. |
| <code>array</code> | $default_args  | Optional, the default state of parameter during adding hook. |
| <code>integer</code> | $accepted_args  | Optional, the limitation of the hook parameters the hook can accept. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_apply_hook" class="anchor"></a>
####  fusion_apply_hook() : mixed

```
 fusion_apply_hook(  $name) : mixed
```

**Summary**

Run the hooks without any output.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $name  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_check_hook" class="anchor"></a>
####  fusion_check_hook() : boolean

```
 fusion_check_hook(string  $name, string  $function) : boolean
```

**Summary**

Checks if there is a hook by the $name and $function specified registered into the hook instance.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_confirm_exit" class="anchor"></a>
####  fusion_confirm_exit() 

```
 fusion_confirm_exit() 
```

**Summary**

JS form exit confirmation if form has changed.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_decode" class="anchor"></a>
####  fusion_decode() : mixed

```
 fusion_decode(string  $value) : mixed
```

**Summary**

Converts string to array/string

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_decrypt" class="anchor"></a>
####  fusion_decrypt() : null&amp;#124;string

```
 fusion_decrypt(string  $value, string  $password) : null&amp;#124;string
```

**Summary**

Decrypt a string

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |
| <code>string</code> | $password  |  |

**Returns:** null&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_detect_installation" class="anchor"></a>
####  fusion_detect_installation() : string

```
 fusion_detect_installation() : string
```

**Summary**

Detect whether the system is installed and return the config file path.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_encode" class="anchor"></a>
####  fusion_encode() : string

```
 fusion_encode(string&amp;#124;array  $value) : string
```

**Summary**

Converts an array/string to string

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $value  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_encrypt" class="anchor"></a>
####  fusion_encrypt() : string

```
 fusion_encrypt(string  $value, string  $password) : string
```

**Summary**

Encrypts a string

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |
| <code>string</code> | $password  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_filter_current_hook" class="anchor"></a>
####  fusion_filter_current_hook() : mixed

```
 fusion_filter_current_hook(  $name) : mixed
```

**Summary**

If hook add once, and only intended to be used once, use this function.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $name  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_filter_hook" class="anchor"></a>
####  fusion_filter_hook() : array

```
 fusion_filter_hook(  $name) : array
```

**Summary**

This one will return output from running all available hooks added under the same namespace in one go and return array.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $name  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_first_words" class="anchor"></a>
####  fusion_first_words() : string

```
 fusion_first_words(string  $text, integer  $limit, string  $suffix = &#039;&amp;hellip;&#039;) : string
```

**Summary**

Trim a text to a number of words.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | ) String to trim. |
| <code>integer</code> | $limit  | The number of words. |
| <code>string</code> | $suffix  | If $text is longer than $limit, $suffix will be appended. |

**Returns:** string - String trimmed to the given length.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_aidlink" class="anchor"></a>
####  fusion_get_aidlink() : string

```
 fusion_get_aidlink() : string
```

**Summary**

Get Aidlink.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_config" class="anchor"></a>
####  fusion_get_config() : string&amp;#124;null

```
 fusion_get_config(integer  $max_level = 7) : string&amp;#124;null
```

**Summary**

Get path of config.php

**Details:**
* File: [autoloader.php](files/autoloader.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $max_level  |  |

**Returns:** string&#124;null - The relative path of the base directory
or NULL if config.php was not found

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_contents" class="anchor"></a>
####  fusion_get_contents() : boolean&amp;#124;string

```
 fusion_get_contents(  $url) : boolean&amp;#124;string
```

**Summary**

cURL method to get any contents for Apache that does not support SSL for remote paths.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $url  |  |

**Returns:** boolean&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_currency" class="anchor"></a>
####  fusion_get_currency() : array&amp;#124;string

```
 fusion_get_currency(string  $iso = NULL, boolean  $description = TRUE) : array&amp;#124;string
```

**Summary**

Get currency symbol by using a 3-letter ISO 4217 currency code.

**Description**

Note that if INTL pecl package is not installed, signs will degrade to ISO4217 code itself

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $iso  | 3-letter ISO 4217 |
| <code>boolean</code> | $description  | Set to false for just symbol |

**Returns:** array&#124;string - Array of currencies or string with one currency.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_detected_language" class="anchor"></a>
####  fusion_get_detected_language() : array

```
 fusion_get_detected_language() : array
```

**Summary**

Get the array of detected languages.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_enabled_languages" class="anchor"></a>
####  fusion_get_enabled_languages() : array

```
 fusion_get_enabled_languages() : array
```

**Summary**

Get the array of enabled languages.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_function" class="anchor"></a>
####  fusion_get_function() : mixed&amp;#124;string

```
 fusion_get_function(string  $function) : mixed&amp;#124;string
```

**Summary**

Load any function and return it's value.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $function  | Function name. |

**Returns:** mixed&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |
| params |  | miexd  ...$args Zero or more parameters to be passed, depending on function. |

<a name="method_fusion_get_groups" class="anchor"></a>
####  fusion_get_groups() : array

```
 fusion_get_groups(array  $remove = array()) : array
```

**Summary**

Gets array of all access levels and user groups.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $remove  | Array of groups you want to exclude from output. |

**Returns:** array - Array of all access levels and user groups.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_language_switch" class="anchor"></a>
####  fusion_get_language_switch() : array

```
 fusion_get_language_switch() : array
```

**Summary**

Get language switch arrays.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_locale" class="anchor"></a>
####  fusion_get_locale() : string&amp;#124;array

```
 fusion_get_locale(string  $key = NULL, array&amp;#124;string  $include_file = &#039;&#039;) : string&amp;#124;array
```

**Summary**

Get locales.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | The key of one locale |
| <code>array&#124;string</code> | $include_file  | The full path of the file which to be included. |

**Returns:** string&#124;array - Associative array of locales or one locale by key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_settings" class="anchor"></a>
####  fusion_get_settings() : array&lt;mixed,string&gt;&amp;#124;string

```
 fusion_get_settings(string  $key = NULL) : array&lt;mixed,string&gt;&amp;#124;string
```

**Summary**

Fetch the settings from the database.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | The key of one setting |

**Returns:** array&lt;mixed,string&gt;&#124;string - Associative array of settings or one setting by key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_template" class="anchor"></a>
#### (deprecated) -  fusion_get_template() : string

```
 fusion_get_template(  $source_file) : string
```

**Summary**

Load a HTML template

**Deprecated**
Deprecatednot used anywhere
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $source_file  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_token" class="anchor"></a>
####  fusion_get_token() : string

```
 fusion_get_token(string  $form_id, integer  $max_tokens = 5) : string
```

**Summary**

Get form tokens.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $form_id  | Form ID. |
| <code>integer</code> | $max_tokens  | Max tokens. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_user" class="anchor"></a>
####  fusion_get_user() : string&amp;#124;array

```
 fusion_get_user(integer  $user_id, string  $key = NULL) : string&amp;#124;array
```

**Summary**

Get the data of any user by ID.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  | The user ID. |
| <code>string</code> | $key  | The key of column. |

**Returns:** string&#124;array - Associative array of all data or one column by key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_userdata" class="anchor"></a>
####  fusion_get_userdata() : string&amp;#124;array

```
 fusion_get_userdata(string  $key = NULL) : string&amp;#124;array
```

**Summary**

Fetch user data of the currently logged in user from database.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | The key of one column. |

**Returns:** string&#124;array - Associative array of all data or one column by key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_get_username" class="anchor"></a>
####  fusion_get_username() : string

```
 fusion_get_username(integer  $user_id) : string
```

**Summary**

Fetch user name by ID.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  | User ID. |

**Returns:** string - Username.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_load_script" class="anchor"></a>
####  fusion_load_script() : string

```
 fusion_load_script(string  $file_path, string  $file_type = &quot;script&quot;, boolean  $html = FALSE, boolean  $cached = TRUE, boolean  $show_warnings = FALSE) : string
```

**Summary**

Cached script loader.

**Description**

This function will cache the path that has been added and avoid duplicates.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $file_path  | The source file. |
| <code>string</code> | $file_type  | Possible value: script, css. |
| <code>boolean</code> | $html  | Return as html tags instead add to output handler. |
| <code>boolean</code> | $cached  | False to invalidate browser's cache. |
| <code>boolean</code> | $show_warnings  | True to show error notices. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_parse_user" class="anchor"></a>
####  fusion_parse_user() : string

```
 fusion_parse_user(string  $user_name, string  $tooltip = &#039;&#039;) : string
```

**Summary**

Tag a user by simply just posting his name like @Nick and if found, returns a tooltip.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $user_name  | @Nick |
| <code>string</code> | $tooltip  | Additional info e.g. ($userdata['user_lastvisit'] - 120 < time() ? 'Online' : 'Offline'). |

**Returns:** string - Tooltip with info.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_remove_hook" class="anchor"></a>
####  fusion_remove_hook() : boolean

```
 fusion_remove_hook(string  $name, string  $function = &#039;&#039;, integer  $que = 10) : boolean
```

**Summary**

Remove hook.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  | The name of the hook, this is your identifier. |
| <code>string</code> | $function  | The callback function to run when the filter runs. |
| <code>integer</code> | $que  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_rename" class="anchor"></a>
####  fusion_rename() 

```
 fusion_rename(string  $origin, string  $target) 
```

**Summary**

Alternative to rename() that works on Windows.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $origin  | The old name. |
| <code>string</code> | $target  | The new name. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_repeat_current_hook" class="anchor"></a>
####  fusion_repeat_current_hook() : mixed

```
 fusion_repeat_current_hook(  $name) : mixed
```

**Summary**

If hook add once, and intended to be used multiple times, use this function.

**Details:**
* File: [hooks_include.php](files/hooks_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $name  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_run_installer" class="anchor"></a>
####  fusion_run_installer() 

```
 fusion_run_installer() 
```

**Summary**

Run the installer or halt the script

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_safe" class="anchor"></a>
####  fusion_safe() : boolean

```
 fusion_safe() : boolean
```

**Summary**

Checks if fusion is safe to proceed next step

**Details:**
* File: [defender.php](files/defender.md)

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_set_cookie" class="anchor"></a>
####  fusion_set_cookie() 

```
 fusion_set_cookie(string  $name, string  $value, integer  $expires, string  $path, string  $domain, boolean  $secure = FALSE, boolean  $httponly = FALSE, string&amp;#124;null  $samesite = NULL) 
```

**Summary**

Send a cookie.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  | The name of the cookie. |
| <code>string</code> | $value  | The value of the cookie. |
| <code>integer</code> | $expires  | The time the cookie expires. |
| <code>string</code> | $path  | The path on the server in which the cookie will be available on. |
| <code>string</code> | $domain  | The (sub)domain that the cookie is available to. |
| <code>boolean</code> | $secure  | Whether the client should send back the cookie only over HTTPS or null to auto-enable this when the request is already using HTTPS. |
| <code>boolean</code> | $httponly  | Whether the cookie will be made accessible only through the HTTP protocol. |
| <code>string&#124;null</code> | $samesite  | Whether the cookie will be available for cross-site requests. Possible value: none | lax | strict |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_sort_table" class="anchor"></a>
####  fusion_sort_table() : string

```
 fusion_sort_table(string  $table_id) : string
```

**Summary**

JavaScript that makes HTML table sortable.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_id  | Table ID |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_stop" class="anchor"></a>
####  fusion_stop() : null

```
 fusion_stop(string  $error_message = &quot;&quot;) : null
```

**Summary**

Declares FUSION_NULL constants to safeguard sensitive code execution.

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $error_message  | The notification text. If present, will show a notice on page load. |

**Returns:** null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_fusion_table" class="anchor"></a>
####  fusion_table() : string

```
 fusion_table(string  $table_id, array  $options = array()) : string
```

**Summary**

Initiliazes Datatables

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $table_id  |  |
| <code>array</code> | $options  | Options for columns parameters (Example)
$options["columns"] = array(
    array("data" => "column_1_name", "orderable"=>FALSE, "width"=>200, "class"=>"min"),
    array("data" => "column_1_name")
)
The response for the item must contains such:
array(
    "data" => array( 0 => array("column_1" => "data", "column_2" => "data"...), 1 => ... ),
    "recordsTotal" => $rows,
    "recordsFiltered" => $max_rows,
    "responsive" => TRUE
) |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get" class="anchor"></a>
####  get() : mixed

```
 get(mixed  $key = NULL, integer  $type = FILTER_DEFAULT, mixed  $flags = NULL) : mixed
```

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  |  |
| <code>integer</code> | $type  |  |
| <code>mixed</code> | $flags  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_all_parent" class="anchor"></a>
####  get_all_parent() : array&amp;#124;integer

```
 get_all_parent(array  $index, integer  $child_id, array  $list = array()) : array&amp;#124;integer
```

**Summary**

Get parent IDs from dbquery_tree() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $index  | Results from dbquery_tree(). |
| <code>integer</code> | $child_id  | Child ID. |
| <code>array</code> | $list  |  |

**Returns:** array&#124;integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_available_languages_list" class="anchor"></a>
#### (deprecated) -  get_available_languages_list() : string

```
 get_available_languages_list(string  $selected_language = &quot;&quot;) : string
```

**Summary**

Create a selection list of possible languages in list.

**Deprecated**
Deprecateduse form_select()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $selected_language  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_breadcrumbs" class="anchor"></a>
####  get_breadcrumbs() : array

```
 get_breadcrumbs() : array
```

**Summary**

Get breadcrumbs

**Details:**
* File: [breadcrumbs.php](files/breadcrumbs.md)

**Returns:** array - Keys of elements: title, link

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_child" class="anchor"></a>
####  get_child() : array

```
 get_child(array  $index, integer  $parent_id, array  $children = array()) : array
```

**Summary**

Get child IDs from dbquery_tree() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $index  | Results from dbquery_tree(). |
| <code>integer</code> | $parent_id  | Parent ID. |
| <code>array</code> | $children  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_color_brightness" class="anchor"></a>
####  get_color_brightness() : float

```
 get_color_brightness(string  $hex) : float
```

**Summary**

Get color brightness by given HEX code

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $hex  | HEX color code. |

**Returns:** float

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_current_url" class="anchor"></a>
####  get_current_url() : string

```
 get_current_url() : string
```

**Summary**

Get current URL.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_depth" class="anchor"></a>
####  get_depth() : integer

```
 get_depth(array  $index, integer  $child_id, integer  $depth = NULL) : integer
```

**Summary**

Get current depth from dbquery_tree() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $index  | Results from dbquery_tree(). |
| <code>integer</code> | $child_id  | Child ID. |
| <code>integer</code> | $depth  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_form_select_chain_index" class="anchor"></a>
####  get_form_select_chain_index() 

```
 get_form_select_chain_index(  $data,   $options) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $data  |  |
| <code></code> | $options  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_get_form_select_opts" class="anchor"></a>
####  get_form_select_opts() 

```
 get_form_select_opts(  $data,   $options,   $id,   $level) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $data  |  |
| <code></code> | $options  |  |
| <code></code> | $id  |  |
| <code></code> | $level  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_get_fusion_field_config" class="anchor"></a>
####  get_fusion_field_config() : array&amp;#124;false&amp;#124;mixed&amp;#124;null

```
 get_fusion_field_config(  $field_name) : array&amp;#124;false&amp;#124;mixed&amp;#124;null
```

**Summary**

Fetches field configurations

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $field_name  |  |

**Returns:** array&#124;false&#124;mixed&#124;null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_hkey" class="anchor"></a>
####  get_hkey() : integer

```
 get_hkey(string  $db, string  $id_col, string  $cat_col, integer  $current_id) : integer
```

**Summary**

Get tree root ID of a child via SQL.

**Description**

Alternative function to get a root of a specific item when dbtree is not available.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $db  | The table name relative to the search. |
| <code>string</code> | $id_col  | The unique id column name of $db. |
| <code>string</code> | $cat_col  | The category id column name of $db. |
| <code>integer</code> | $current_id  | The current id of the item relative to the ancestor root. |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_http_response_code" class="anchor"></a>
####  get_http_response_code() : false&amp;#124;string

```
 get_http_response_code(string  $url) : false&amp;#124;string
```

**Summary**

Get HTTP response code.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | URL. |

**Returns:** false&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_image" class="anchor"></a>
####  get_image() : string

```
 get_image(string  $image, string  $alt = &quot;&quot;, string  $style = &quot;&quot;, string  $title = &quot;&quot;, string  $atts = &quot;&quot;) : string
```

**Summary**

Get the imagepath or <img> tag.

**Details:**
* File: [system_images.php](files/system_images.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $image  | The name of the image. Default system images: up, down, imagenotfound, left, right, noavatar, panel_on, panel_off |
| <code>string</code> | $alt  | The alt attribute of the image. |
| <code>string</code> | $style  | The style attribute of the image. |
| <code>string</code> | $title  | The title attribute of the image. |
| <code>string</code> | $atts  | Custom attributes of the image. |

**Returns:** string - The path of the image if the first argument is given, but others not. Otherwise <img> tag.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_microtime" class="anchor"></a>
#### (deprecated) -  get_microtime() : float

```
 get_microtime() : float
```

**Summary**

Current microtime as float to calculate script start/end time

**Deprecated**
Deprecatedsince version 9.00, use microtime(TRUE) instead
**Details:**
* File: [deprecated.php](files/deprecated.md)

**Returns:** float

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_parent" class="anchor"></a>
####  get_parent() : integer

```
 get_parent(array  $index, integer  $child_id) : integer
```

**Summary**

Get immediate parent ID from dbquery_tree() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $index  | Results from dbquery_tree(). |
| <code>integer</code> | $child_id  | Child ID. |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_parent_array" class="anchor"></a>
####  get_parent_array() : array

```
 get_parent_array(array  $data, integer  $child_id) : array
```

**Summary**

Get immediate parent array from dbquery_tree_full() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | Results from dbquery_tree_full(). |
| <code>integer</code> | $child_id  | Child ID. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_root" class="anchor"></a>
####  get_root() : integer

```
 get_root(array  $index, integer  $child_id) : integer
```

**Summary**

Get tree root ID of a child from dbquery_tree() result.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $index  | Results from dbquery_tree() |
| <code>integer</code> | $child_id  | Child ID. |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_rowstart" class="anchor"></a>
####  get_rowstart() : integer

```
 get_rowstart(string  $key, integer  $max_limit) : integer
```

**Summary**

Get max rowstart from a query to prevent renumbering pagenav.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | $_GET key |
| <code>integer</code> | $max_limit  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_settings" class="anchor"></a>
####  get_settings() : mixed&amp;#124;null

```
 get_settings(string  $settings_inf, string  $key = NULL) : mixed&amp;#124;null
```

**Summary**

Get all the settings for the given infusion.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $settings_inf  | The infusion you'll get the settings for. |
| <code>string</code> | $key  | The key of one setting. |

**Returns:** mixed&#124;null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_theme_settings" class="anchor"></a>
####  get_theme_settings() : array&amp;#124;boolean

```
 get_theme_settings(string  $theme_folder) : array&amp;#124;boolean
```

**Summary**

Get the theme settings from database.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme_folder  | The name of the theme folder. |

**Returns:** array&#124;boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_get_title" class="anchor"></a>
####  get_title() : string

```
 get_title() : string
```

**Summary**

Get current page title

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getcategory" class="anchor"></a>
#### (deprecated) -  getcategory() : array

```
 getcategory(string  $cat) : array
```

**Summary**

for sitelinks - not hierarchy

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $cat  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getcolorname" class="anchor"></a>
####  getcolorname() : string

```
 getcolorname(string  $id) : string
```

**Summary**

Get the color name.

**Details:**
* File: [html_buttons_include.php](files/html_buttons_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  | Color locale ID |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getgroupdata" class="anchor"></a>
####  getgroupdata() : array

```
 getgroupdata(integer  $group_id) : array
```

**Summary**

Get the data of the access level or user group

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group_id  | The ID of the group. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getgroupname" class="anchor"></a>
####  getgroupname() : string

```
 getgroupname(integer  $group_id, boolean  $return_desc = FALSE, boolean  $return_icon = FALSE) : string
```

**Summary**

Get the name of the access level or user group.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group_id  | The ID of the group or access level to which you want to get a name. |
| <code>boolean</code> | $return_desc  | If true, description will be returned instead of name. |
| <code>boolean</code> | $return_icon  | If true, icon will be returned next to name. |

**Returns:** string - The name or icon or description of the given group, null if does not exist.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getimg" class="anchor"></a>
####  getimg() 

```
 getimg(  $url) 
```

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $url  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getnotices" class="anchor"></a>
####  getnotices() : array

```
 getnotices(string&amp;#124;array  $key = FUSION_SELF, boolean  $delete = TRUE) : array
```

**Summary**

Retrievs all notices for the group identified by the key provided/

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $key  | The key(s) identifying a group or more holding notices, by default the page name in which the notice was set. |
| <code>boolean</code> | $delete  | Whether to delete or keep a notice message after it was accessed.
                            This only works if the notice was set or added while having $remove_after_access set to false |

**Returns:** array - The notices for the group identified by the provided key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getsuspension" class="anchor"></a>
####  getsuspension() : mixed

```
 getsuspension(integer  $type, boolean  $action = FALSE) : mixed
```

**Summary**

Get suspension.

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $type  |  |
| <code>boolean</code> | $action  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getusergroups" class="anchor"></a>
####  getusergroups() : array

```
 getusergroups() : array
```

**Summary**

Gets all access levels and user groups and make one array out of them for easy access and usage.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** array - Array of all access levels and user groups.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getuserlevel" class="anchor"></a>
####  getuserlevel() : string

```
 getuserlevel(integer  $userlevel) : string
```

**Summary**

Get a user level's name by the numeric code of level.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $userlevel  | Level code. |

**Returns:** string - The name of the given user level, null if does not exist.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_getuserstatus" class="anchor"></a>
####  getuserstatus() : string&amp;#124;null

```
 getuserstatus(integer  $userstatus) : string&amp;#124;null
```

**Summary**

Get a user status by the numeric code of status.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $userstatus  | Status code 0 - 8. |

**Returns:** string&#124;null - The name of the given user status, null if does not exist.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_groupaccess" class="anchor"></a>
####  groupaccess() : string

```
 groupaccess(string  $field, string  $delim = &#039;,&#039;) : string
```

**Summary**

Getting the access levels used when asking the database for data.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $field  | MySQL field from which you want to check access. |
| <code>string</code> | $delim  | Delimiter. |

**Returns:** string - The part of WHERE clause, always returns a condition.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_handle_output" class="anchor"></a>
####  handle_output() : string

```
 handle_output(string  $output) : string
```

**Summary**

Execute the output handlers

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $output  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_hash_equals" class="anchor"></a>
####  hash_equals() 

```
 hash_equals(  $str1,   $str2) 
```

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $str1  |  |
| <code></code> | $str2  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_hasnotice" class="anchor"></a>
####  hasnotice() : boolean

```
 hasnotice(string  $key = FUSION_SELF) : boolean
```

**Summary**

Checks whether a group identified by the key provided has any notices

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | The key identifying a group or more holding notices, by default the page name in which the notice was set |

**Returns:** boolean - Ture if the group has any notices.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_header_content_type" class="anchor"></a>
####  header_content_type() 

```
 header_content_type(string  $value) 
```

**Summary**

Sets a header type

**Details:**
* File: [ajax_include.php](files/ajax_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_hide_email" class="anchor"></a>
####  hide_email() : string

```
 hide_email(string  $email, string  $title = &quot;&quot;, string  $subject = &quot;&quot;) : string
```

**Summary**

Hide email from robots that have JavaScript disabled, as it requires JavaScript to view email.

**Description**

Create a "mailto" link for the email address

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $email  | The email you want to hide from robots. |
| <code>string</code> | $title  | The text of the link. |
| <code>string</code> | $subject  | A subject for a mail message if someone opens a link, and it opens in the mail client. |

**Returns:** string - If browser has JavaScript enabled, email will be displayed correctly,
               otherwise it will be hidden and difficult for a robot to decrypt.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_highlight_words" class="anchor"></a>
####  highlight_words() : string

```
 highlight_words(array  $words, string  $subject) : string
```

**Summary**

Highlights given words in string.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $words  | The words to highlight. |
| <code>string</code> | $subject  | Text that contains a word (s) that should be highlighted. |

**Returns:** string - Words highlighted in the string.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_image_exists" class="anchor"></a>
####  image_exists() : string

```
 image_exists(string  $dir, string  $image) : string
```

**Summary**

Find another available image name based on the image in the folder.

**Details:**
* File: [photo_functions_include.php](files/photo_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $dir  | The directory to check for the image, remember a / at the end of the directory path. |
| <code>string</code> | $image  | The image inside the directory you want to check for. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_img_mimetypes" class="anchor"></a>
####  img_mimetypes() : array

```
 img_mimetypes() : array
```

**Summary**

Array of image mime types.

**Details:**
* File: [mimetypes_include.php](files/mimetypes_include.md)

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_in_group" class="anchor"></a>
####  in_group() : string

```
 in_group(string  $column_name, string  $value, string  $delim = &#039;,&#039;) : string
```

**Summary**

SQL statement helper to find values in between dots.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $column_name  |  |
| <code>string</code> | $value  |  |
| <code>string</code> | $delim  |  |

**Returns:** string - Example: language column contains '.BL.NS.NC.NG'
         SELECT * FROM ".DB." WHERE ".in_group(language, 'BL')."

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_infinite_scroll" class="anchor"></a>
####  infinite_scroll() : string

```
 infinite_scroll(string  $scroll_url, integer  $rowstart, integer  $count, string  $getname = &#039;rowstart&#039;, string  $http_query = &#039;&#039;) : string
```

**Summary**

Infinite scroll pagination.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $scroll_url  | The ajax script that loads the content. |
| <code>integer</code> | $rowstart  | The number of the first listed item. |
| <code>integer</code> | $count  | The number of entries displayed on one page. |
| <code>string</code> | $getname  | The name of the $_GET parameter that contains the start number. |
| <code>string</code> | $http_query  | Additional http query. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_infusion_exists" class="anchor"></a>
####  infusion_exists() : boolean

```
 infusion_exists(string  $infusion_folder) : boolean
```

**Summary**

Check whether an infusion is installed or not from the infusions table.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $infusion_folder  |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_is_blacklisted" class="anchor"></a>
####  is_blacklisted() : boolean

```
 is_blacklisted() : boolean
```

**Summary**

Check if user's full or partial ip is blacklisted.

**Details:**
* File: [ip_handling_include.php](files/ip_handling_include.md)

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_is_json" class="anchor"></a>
####  is_json() : boolean

```
 is_json(string  $string) : boolean
```

**Summary**

Checks whether a string is JSON or not.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $string  | The string to be checked. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_isnum" class="anchor"></a>
####  isnum() : boolean

```
 isnum(mixed  $value, boolean  $decimal = FALSE, boolean  $negative = FALSE) : boolean
```

**Summary**

Validate numeric input.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $value  | The value to be checked. |
| <code>boolean</code> | $decimal  | Decimals. |
| <code>boolean</code> | $negative  | Negative numbers. |

**Returns:** boolean - True if the value is a number.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_itemoptions" class="anchor"></a>
#### (deprecated) -  itemoptions() : string

```
 itemoptions(  $item_type,   $item_id) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $item_type  |  |
| <code></code> | $item_id  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_jsminify" class="anchor"></a>
####  jsminify() : string

```
 jsminify(string  $code) : string
```

**Summary**

Minify JS code.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $code  | Unminified code. |

**Returns:** string - Minified code.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_label" class="anchor"></a>
####  label() : string

```
 label(string  $label, array  $options = array()) : string
```

**Summary**

Creates label.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $label  |  |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_lang_switcher" class="anchor"></a>
####  lang_switcher() 

```
 lang_switcher(boolean  $icon = TRUE) 
```

**Summary**

Language switcher function.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $icon  | Set to false to hide the icon. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_load_select2_script" class="anchor"></a>
####  load_select2_script() 

```
 load_select2_script() 
```

**Summary**

Load Select2

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_location_search" class="anchor"></a>
####  location_search() 

```
 location_search(  $q) 
```

**Details:**
* File: [dynamics\includes\form_geomap.php](files/dynamics.includes.form_geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $q  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_lorem_ipsum" class="anchor"></a>
####  lorem_ipsum() : string

```
 lorem_ipsum(integer  $length) : string
```

**Summary**

Generate random lorem ipsum text by given length.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $length  | String length. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_make_order_opts" class="anchor"></a>
####  make_order_opts() 

```
 make_order_opts(  $result,   $id_col,   $cat_col,   $title_col,   $order_col) 
```

**Details:**
* File: [dynamics\includes\form_ordering.php](files/dynamics.includes.form_ordering.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $result  |  |
| <code></code> | $id_col  |  |
| <code></code> | $cat_col  |  |
| <code></code> | $title_col  |  |
| <code></code> | $order_col  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_make_page_breadcrumbs" class="anchor"></a>
####  make_page_breadcrumbs() 

```
 make_page_breadcrumbs(array  $tree_index, array  $tree_full, string  $id_col, string  $title_col, string  $getname = &quot;rownav&quot;) 
```

**Summary**

Hierarchy Page Breadcrumbs, generates breadcrumbs on all your category needs.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $tree_index  | dbquery_tree() or tree_index(). |
| <code>array</code> | $tree_full  | dbquery_tree_full(). |
| <code>string</code> | $id_col  | The name of the category id column. |
| <code>string</code> | $title_col  | The name of the category nmae column. |
| <code>string</code> | $getname  | The name of the $_GET parameter. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makefilelist" class="anchor"></a>
####  makefilelist() : array

```
 makefilelist(string  $folder, string  $filter = &quot;&quot;, boolean  $sort = TRUE, string  $type = &quot;files&quot;, string  $ext_filter = &quot;&quot;) : array
```

**Summary**

Create a list of files or folders and store them in an array.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  | Path to folder. |
| <code>string</code> | $filter  | The names of the filtered folders and files separated by |, false to use default filter. |
| <code>boolean</code> | $sort  | False if you don't want to sort the result. |
| <code>string</code> | $type  | Possible value: files, folders. |
| <code>string</code> | $ext_filter  | File extensions separated by |, only when $type is 'files'. |

**Returns:** array - Array of all items.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makefileopts" class="anchor"></a>
#### (deprecated) -  makefileopts() : string

```
 makefileopts(array  $options, string  $selected = &quot;&quot;) : string
```

**Summary**

Create <option></option> from the entries in a given array.

**Deprecated**
Deprecateduse form_select()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $options  | Options. |
| <code>string</code> | $selected  | The item in the options that you want to select by default. |

**Returns:** string - Array as a list of options for a select.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makepagenav" class="anchor"></a>
####  makepagenav() : string&amp;#124;boolean

```
 makepagenav(integer  $rowstart, integer  $count, integer  $total, integer  $range = 3, string  $link = &quot;&quot;, string  $getname = &quot;rowstart&quot;, boolean  $button = FALSE) : string&amp;#124;boolean
```

**Summary**

Creates page navigation.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $rowstart  | The number of the first listed item. |
| <code>integer</code> | $count  | The number of entries displayed on one page. |
| <code>integer</code> | $total  | The total entries which should be displayed. |
| <code>integer</code> | $range  | The number of page buttons displayed and the range of them. |
| <code>string</code> | $link  | The base url before the appended part. |
| <code>string</code> | $getname  | The name of the $_GET parameter that contains the start number. |
| <code>boolean</code> | $button  | Displays as button. |

**Returns:** string&#124;boolean - HTML navigation. False if $count is invalid.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makepagenav_filter" class="anchor"></a>
####  makepagenav_filter() 

```
 makepagenav_filter(  $start,   $count,   $total,   $range,   $link = &quot;&quot;,   $getname = &quot;rowstart&quot;,   $array = FALSE) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $start  |  |
| <code></code> | $count  |  |
| <code></code> | $total  |  |
| <code></code> | $range  |  |
| <code></code> | $link  |  |
| <code></code> | $getname  |  |
| <code></code> | $array  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makepagenav_js" class="anchor"></a>
####  makepagenav_js() 

```
 makepagenav_js(  $start,   $count,   $total,   $range,   $link = &quot;&quot;,   $getname = &quot;rowstart&quot;,   $array = FALSE) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $start  |  |
| <code></code> | $count  |  |
| <code></code> | $total  |  |
| <code></code> | $range  |  |
| <code></code> | $link  |  |
| <code></code> | $getname  |  |
| <code></code> | $array  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_makepagenav_nojs" class="anchor"></a>
####  makepagenav_nojs() 

```
 makepagenav_nojs(  $start,   $count,   $total,   $range,   $link = &quot;&quot;,   $getname = &quot;rowstart&quot;) 
```

**Details:**
* File: [dynamics\assets\filter\filter.inc.php](files/dynamics.assets.filter.filter.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $start  |  |
| <code></code> | $count  |  |
| <code></code> | $total  |  |
| <code></code> | $range  |  |
| <code></code> | $link  |  |
| <code></code> | $getname  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_map_country" class="anchor"></a>
####  map_country() 

```
 map_country(  $states,   $country) 
```

**Details:**
* File: [dynamics\includes\form_geomap.php](files/dynamics.includes.form_geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $states  |  |
| <code></code> | $country  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_map_region" class="anchor"></a>
####  map_region() 

```
 map_region(  $states) 
```

**Details:**
* File: [dynamics\includes\form_geomap.php](files/dynamics.includes.form_geomap.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $states  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_max_server_upload" class="anchor"></a>
####  max_server_upload() : mixed

```
 max_server_upload() : mixed
```

**Summary**

Get max server upload limit.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_member_nav" class="anchor"></a>
####  member_nav() 

```
 member_nav(string  $second = &quot;&quot;, string  $third = &quot;&quot;) 
```

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $second  |  |
| <code>string</code> | $third  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_member_url" class="anchor"></a>
####  member_url() : string

```
 member_url(  $step,   $user_id) : string
```

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $step  |  |
| <code></code> | $user_id  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_mimetypes" class="anchor"></a>
####  mimetypes() : array

```
 mimetypes() : array
```

**Summary**

Array of mime types.

**Details:**
* File: [mimetypes_include.php](files/mimetypes_include.md)

**Returns:** array - Map of extensions to mime types.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_modalfooter" class="anchor"></a>
####  modalfooter() : string

```
 modalfooter(string  $content, boolean  $dismiss = FALSE) : string
```

**Summary**

Adds a modal footer in between openmodal and closemodal.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $content  |  |
| <code>boolean</code> | $dismiss  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_multilang_column" class="anchor"></a>
####  multilang_column() : string

```
 multilang_column(string  $column) : string
```

**Summary**

SQL language value

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $column  | Column name. |

**Returns:** string - - calculated conditions
Usage: $result = dbquery("SELECT * FROM ".DB_NEWS." WHERE ".multilang_column('news_subject')." = '".$data['news_subject']."'");
Usage: $tree_data = dbquery_tree_full(DB_NEWS_CATS, "news_cat_id", "news_cat_parent", "order by ".multilang_column("news_cat_name"));

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_multilang_table" class="anchor"></a>
####  multilang_table() : boolean

```
 multilang_table(string  $rights) : boolean
```

**Summary**

Check multilang tabl.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  | Multilang rights. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_new_array" class="anchor"></a>
####  new_array() : array&amp;#124;false

```
 new_array(array  $array, array  $array2 = array()) : array&amp;#124;false
```

**Summary**

Short hand to build/combines an array

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  | Initial array to create with keys named in a non multidimensional single array.
                     This will create a multidimensional blank array.
                     Example:
                     ['column', 'coumn2', 'column3'] |
| <code>array</code> | $array2  | Override. An array default value that consist of keys and defined values.
                     ['column' => 'default'] |

**Returns:** array&#124;false

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_newscat" class="anchor"></a>
#### (deprecated) -  newscat() : string

```
 newscat(  $info, string  $sep = &quot;&quot;, string  $class = &quot;&quot;) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code>string</code> | $sep  |  |
| <code>string</code> | $class  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_newsopts" class="anchor"></a>
#### (deprecated) -  newsopts() : string

```
 newsopts(  $info,   $sep, string  $class = &quot;&quot;) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code></code> | $sep  |  |
| <code>string</code> | $class  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_newsposter" class="anchor"></a>
#### (deprecated) -  newsposter() : string

```
 newsposter(  $info, string  $sep = &quot;&quot;, string  $class = &quot;&quot;) : string
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $info  |  |
| <code>string</code> | $sep  |  |
| <code>string</code> | $class  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_normalize" class="anchor"></a>
####  normalize() : string

```
 normalize(string  $value) : string
```

**Summary**

Replaces special characters in a string with their "non-special" counterpart.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  | String to normalize. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_opencollapse" class="anchor"></a>
####  opencollapse() : string

```
 opencollapse(string  $id) : string
```

**Summary**

Create accordion.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  | Unique accordion ID. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_opencollapsebody" class="anchor"></a>
####  opencollapsebody() : string

```
 opencollapsebody(string  $title, string  $unique_id, string  $grouping_id, boolean  $active = FALSE, string  $class = NULL) : string
```

**Summary**

Create collapsing panel.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $title  | Panel title. |
| <code>string</code> | $unique_id  | Panel ID. |
| <code>string</code> | $grouping_id  | Parent's accordion ID. |
| <code>boolean</code> | $active  | Panel state. |
| <code>string</code> | $class  | Panel CSS class. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_openeditortab" class="anchor"></a>
####  openeditortab() 

```
 openeditortab(  $tab_title,   $link_active_arrkey,   $id,   $link = FALSE,   $class = FALSE,   $getname = &quot;section&quot;) 
```

**Details:**
* File: [dynamics\includes\form_textarea.php](files/dynamics.includes.form_textarea.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $tab_title  |  |
| <code></code> | $link_active_arrkey  |  |
| <code></code> | $id  |  |
| <code></code> | $link  |  |
| <code></code> | $class  |  |
| <code></code> | $getname  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_openform" class="anchor"></a>
####  openform() : string

```
 openform(string  $form_name, string  $method, string  $action_url = FORM_REQUEST, array  $options = array()) : string
```

**Summary**

The function should be able used to replace conventional <form> tags to provide an enhanced feature to your application.

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $form_name  | Form ID. |
| <code>string</code> | $method  | Possible value: post, get. |
| <code>string</code> | $action_url  | Form current uri. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_openmodal" class="anchor"></a>
####  openmodal() : string

```
 openmodal(string  $id, string  $title, array  $options = array()) : string
```

**Summary**

Generate modal.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $id  | Unique modal ID. |
| <code>string</code> | $title  | Modal title. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_opensidex" class="anchor"></a>
#### (deprecated) -  opensidex() 

```
 opensidex(null  $title = NULL) 
```

**Deprecated**
Deprecateduse openside()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>null</code> | $title  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_opentab" class="anchor"></a>
####  opentab() : string

```
 opentab(array  $tab_title, string  $link_active_arrkey, string  $id, boolean  $link = FALSE, string  $class = NULL, string  $getname = &quot;section&quot;, array  $cleanup_get = array(), boolean  $remember = FALSE) : string
```

**Summary**

Render tab links.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $tab_title  | Multidimension array consisting of keys title, id, icon. |
| <code>string</code> | $link_active_arrkey  | tab_active() function or the $_GET request to match the $tab_title['id']. |
| <code>string</code> | $id  | Unique ID. |
| <code>boolean</code> | $link  | False for jquery, true for php (will reload page). |
| <code>string</code> | $class  | CSS class for the nav. |
| <code>string</code> | $getname  | Set getname and turn tabs into the link that listens to getname. |
| <code>array</code> | $cleanup_get  | The request key that needs to be deleted. |
| <code>boolean</code> | $remember  | Set to true to automatically remember tab using cookie.

Example:
$tabs['title'][] = "Tab 1";
$tabs['id'][] = "tab1";
$tabs['title'][] = "Tab 2";
$tabs['id'][] = "tab2";
$tab_active = tab_active($tabs, 0);

Jquery:
echo opentab($tabs, $tab_active, 'myTab', FALSE, 'nav-pills', 'ref', ['action', 'subaction']);

PHP:
echo opentab($tabs, $_GET['ref'], 'myTab', TRUE, 'nav-pills', 'ref', ['action', 'subaction']);
echo opentab($tabs, $_GET['ref'], 'myTab', TRUE, 'nav-pills', 'ref', ['*']); // clear all |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_opentabbody" class="anchor"></a>
####  opentabbody() : string

```
 opentabbody(string  $tab_title, string  $tab_id, string  $link_active_arrkey = NULL, boolean  $link = FALSE, string  $key = NULL) : string
```

**Summary**

Creates tab body.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $tab_title  | Deprecated, however this function is replaceable, and the params are accessible. |
| <code>string</code> | $tab_id  | Tab id from $tabs['id']. |
| <code>string</code> | $link_active_arrkey  | tab_active() function or the $_GET request to match the $tabd['id']. |
| <code>boolean</code> | $link  | Deprecated, however this function is replaceable, and the params are accessible. |
| <code>string</code> | $key  | Set getname and turn tabs into link that listens to getname. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_pageaccess" class="anchor"></a>
####  pageaccess() 

```
 pageaccess(string  $rights, boolean  $debug = FALSE) 
```

**Summary**

Check the user has rights and redirect if the user does not have rights for the page.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rights  | Rights you want to check for the administrator. |
| <code>boolean</code> | $debug  | For debugging purposes. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_panelbutton" class="anchor"></a>
####  panelbutton() : string

```
 panelbutton(string  $state, string  $bname) : string
```

**Summary**

Show the collapse or expand a button for panels which are collapsible.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $state  | Panel state. |
| <code>string</code> | $bname  | Button name. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_panelstate" class="anchor"></a>
####  panelstate() : string

```
 panelstate(string  $state, string  $bname, string  $element = &quot;div&quot;) : string
```

**Summary**

Checks the state of a panel.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $state  | Panel state. Possible value: on, off |
| <code>string</code> | $bname  | Button name. |
| <code>string</code> | $element  | Element name. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parse_image_dir" class="anchor"></a>
####  parse_image_dir() : string

```
 parse_image_dir(string  $data, string  $prefix_ = &quot;&quot;) : string
```

**Summary**

Parse and force image/ to own directory.

**Description**

Neutralize all image dir levels and convert image to pf image folder

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $data  | String to parse. |
| <code>string</code> | $prefix_  | Image folder. |

**Returns:** string - Parsed string.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parse_text" class="anchor"></a>
####  parse_text() : string

```
 parse_text(string  $value, array  $options = array()) : string
```

**Summary**

Parse BBCodes, smileys and any special characters to HTML string.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  | String with unparsed text. |
| <code>array</code> | $options  | Array of options. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parse_textarea" class="anchor"></a>
#### (deprecated) -  parse_textarea() : string

```
 parse_textarea(string  $value, boolean  $parse_smileys = TRUE, boolean  $parse_bbcode = TRUE, boolean  $decode = TRUE, string  $default_image_folder = IMAGES, boolean  $add_line_breaks = FALSE, boolean  $descript = TRUE) : string
```

**Summary**

Interpret output to match input of textarea having both bbcode, html and tinymce buttons

**Deprecated**
Deprecateduse parse_text()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $value  |  |
| <code>boolean</code> | $parse_smileys  |  |
| <code>boolean</code> | $parse_bbcode  |  |
| <code>boolean</code> | $decode  |  |
| <code>string</code> | $default_image_folder  |  |
| <code>boolean</code> | $add_line_breaks  |  |
| <code>boolean</code> | $descript  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parsebytesize" class="anchor"></a>
####  parsebytesize() : string

```
 parsebytesize(integer  $size, integer  $decimals = 2, boolean  $dir = FALSE) : string
```

**Summary**

Translate bytes into kB, MB, GB or TB.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $size  | The number of bytes. |
| <code>integer</code> | $decimals  | The number of decimals. |
| <code>boolean</code> | $dir  | True if it is the size of a directory. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parsesmileys" class="anchor"></a>
####  parsesmileys() : string

```
 parsesmileys(string  $message) : string
```

**Summary**

Parse the smileys in string and display smiley codes as smiley images.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $message  | A string that should have parsed smileys. |

**Returns:** string - String with parsed smiley codes as smiley images ready for display.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_parseubb" class="anchor"></a>
####  parseubb() : string

```
 parseubb(string  $text, string  $selected = &quot;&quot;, boolean  $descript = TRUE) : string
```

**Summary**

Parse BBCodes in the given string.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | A string that contains the text to be parsed. |
| <code>string</code> | $selected  | The names of the required bbcodes to parse, separated by |. |
| <code>boolean</code> | $descript  | Sanitize text. |

**Returns:** string - Parsed string.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_phpentities" class="anchor"></a>
####  phpentities() : string

```
 phpentities(string  $text) : string
```

**Summary**

Converts all applicable characters to HTML entities.

**Description**

htmlentities is too agressive so we use this function.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | The input string. |

**Returns:** string - Encoded string.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_post" class="anchor"></a>
####  post() : mixed

```
 post(mixed  $key, integer  $type = FILTER_DEFAULT, mixed  $flags = NULL) : mixed
```

**Summary**

Sanitizes $_POST by name

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  | input_name |
| <code>integer</code> | $type  |  |
| <code>mixed</code> | $flags  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_post_array" class="anchor"></a>
####  post_array() : array

```
 post_array(mixed  $key) : array
```

**Summary**

Sanitizes input

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $key  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_preg_check" class="anchor"></a>
####  preg_check() : boolean

```
 preg_check(string  $expression, mixed  $value) : boolean
```

**Summary**

Custom preg_match function.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $expression  | The expression to search for. |
| <code>mixed</code> | $value  | The input string. |

**Returns:** boolean - FALSE when $value is an array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_print_p" class="anchor"></a>
####  print_p() : string

```
 print_p(mixed  $data, boolean  $modal = FALSE, boolean  $print = TRUE) : string
```

**Summary**

Prints human-readable information about a variable.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $data  | The expression to be printed. |
| <code>boolean</code> | $modal  | Dump info in the modal. |
| <code>boolean</code> | $print  | Dump info in <pre> tag. |

**Returns:** string - The value of the variable.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_profile_link" class="anchor"></a>
####  profile_link() : string

```
 profile_link(integer  $user_id, string  $user_name, integer  $user_status, string  $class = &quot;profile-link&quot;, boolean  $display_link = TRUE) : string
```

**Summary**

User profile link.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |
| <code>string</code> | $user_name  |  |
| <code>integer</code> | $user_status  |  |
| <code>string</code> | $class  | CSS class for the profile link. |
| <code>boolean</code> | $display_link  | Allow clicking on the name, otherwise display only the name. |

**Returns:** string - Link to the user's account along with the user name correctly depending on the user's status.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_progress_bar" class="anchor"></a>
####  progress_bar() : string

```
 progress_bar(integer&amp;#124;array&lt;mixed,integer&gt;  $num, string&amp;#124;array&lt;mixed,string&gt;  $title = NULL, array  $options = array()) : string
```

**Summary**

Render a progress bar.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer&#124;array&lt;mixed,integer&gt;</code> | $num  | Max of 100 or array of numbers. |
| <code>string&#124;array&lt;mixed,string&gt;</code> | $title  | Label for the progress bar or array with multiple titles. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_random_filename" class="anchor"></a>
####  random_filename() : string

```
 random_filename(string  $filename) : string
```

**Summary**

Generate random filename.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filename  | The filename. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_random_string" class="anchor"></a>
####  random_string() : string

```
 random_string(integer  $length = 6, boolean  $letters_only = FALSE) : string
```

**Summary**

Generate random string.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $length  | The length of the string. |
| <code>boolean</code> | $letters_only  | Only letters. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_redirect" class="anchor"></a>
####  redirect() 

```
 redirect(string  $location, boolean  $delay = FALSE, boolean  $script = FALSE, integer  $code = 200) 
```

**Summary**

Redirect to internal or external URL.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $location  | Desintation URL. |
| <code>boolean</code> | $delay  | meta refresh delay. |
| <code>boolean</code> | $script  | True if you want to redirect via javascript. |
| <code>integer</code> | $code  | HTTP status code to send. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_redirect_img_dir" class="anchor"></a>
####  redirect_img_dir() 

```
 redirect_img_dir(string  $source, string  $target) 
```

**Summary**

Replace a part in each image path.

**Details:**
* File: [system_images.php](files/system_images.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source  | Source path. |
| <code>string</code> | $target  | Target path. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_reduce_tree" class="anchor"></a>
####  reduce_tree() : array

```
 reduce_tree(array  $result, string  $id_col) : array
```

**Summary**

Reduce the results of a hierarchy tree array to a non multidimensional
single output value while preserving keys.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $result  | Results from dbquery_tree_full() or dbquery_tree(). |
| <code>string</code> | $id_col  | ID column. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_remove_notice" class="anchor"></a>
####  remove_notice() 

```
 remove_notice(string&amp;#124;array  $key = array(&#039;all&#039;, FUSION_SELF, FUSION_REQUEST)) 
```

**Summary**

Remove notice

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $key  | The key(s) identifying a group or more holding notices. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_render_breadcrumbs" class="anchor"></a>
####  render_breadcrumbs() : string

```
 render_breadcrumbs(string  $key = &#039;default&#039;) : string
```

**Summary**

Render breadcrumbs.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  | Instance key. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_render_favicons" class="anchor"></a>
####  render_favicons() : string

```
 render_favicons(string  $folder = IMAGES . &#039;favicons/&#039;) : string
```

**Summary**

Show meta tags for favicons.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $folder  | The folder where the icons are. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_render_user_tags" class="anchor"></a>
####  render_user_tags() : string

```
 render_user_tags(array  $data, string  $tooltip) : string
```

**Summary**

Render user tags template.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | User data. |
| <code>string</code> | $tooltip  | The tooltip string. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_rendernotices" class="anchor"></a>
####  rendernotices() : string

```
 rendernotices(array  $notices) : string
```

**Summary**

Renders notices

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $notices  | The array contaning notices. |

**Returns:** string - The notices formatted as HTML.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_replace_in_output" class="anchor"></a>
####  replace_in_output() 

```
 replace_in_output(string  $target, string  $replace, string  $modifiers = &quot;&quot;) 
```

**Summary**

Replace something in the output using regexp

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $target  | Regexp pattern without delimiters |
| <code>string</code> | $replace  | The new content |
| <code>string</code> | $modifiers  | Regexp modifiers |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_rowstart_count" class="anchor"></a>
####  rowstart_count() : float

```
 rowstart_count(integer  $total, integer  $count, integer  $range = 3) : float
```

**Summary**

Rowstart count.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $total  |  |
| <code>integer</code> | $count  |  |
| <code>integer</code> | $range  |  |

**Returns:** float

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_rrmdir" class="anchor"></a>
####  rrmdir() 

```
 rrmdir(string  $dir) 
```

**Summary**

Recursively remove folder and all files/subdirectories.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $dir  | Path to the folder. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sanitize_array" class="anchor"></a>
####  sanitize_array() : array

```
 sanitize_array(array  $array = array()) : array
```

**Summary**

Sanitizes an array

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sanitizer" class="anchor"></a>
####  sanitizer() : string

```
 sanitizer(mixed  $value, string  $default = &#039;&#039;, boolean  $input_name = FALSE, boolean  $is_multiLang = FALSE) : string
```

**Summary**

Verify and Sanitize Inputs with input_name
A more secured method

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>mixed</code> | $value  | input_name |
| <code>string</code> | $default  |  |
| <code>boolean</code> | $input_name  |  |
| <code>boolean</code> | $is_multiLang  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_save_user_log" class="anchor"></a>
####  save_user_log() 

```
 save_user_log(integer  $user_id, string  $column_name, string  $new_value, string  $old_value) 
```

**Summary**

Log user actions.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  | User ID. |
| <code>string</code> | $column_name  | Affected column. |
| <code>string</code> | $new_value  | New value. |
| <code>string</code> | $old_value  | Old value. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_search_field" class="anchor"></a>
####  search_field() : string

```
 search_field(array  $columns, string  $text) : string
```

**Summary**

Single column search.

**Description**

used to make searches on field
echo search_field(['admin_title', 'admin_link'], 'ac c d ghi');

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $columns  | Table columns. |
| <code>string</code> | $text  | Any string. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_select2csspath" class="anchor"></a>
####  select2csspath() : string

```
 select2csspath() : string
```

**Details:**
* File: [dynamics\includes\form_main.php](files/dynamics.includes.form_main.md)
* See Also:
 * [\load_select2_script()](namespaces/default.md#function_load_select2_script)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_send_pm" class="anchor"></a>
####  send_pm() 

```
 send_pm(integer  $to, integer  $from, string  $subject, string  $message, string  $smileys = &quot;y&quot;, boolean  $to_group = FALSE) 
```

**Summary**

Sends a Private Message to specified user with email notification if the receiver has enabled it.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $to  | Recepient either group_id or user_id |
| <code>integer</code> | $from  | Sender's user id |
| <code>string</code> | $subject  | Message subject |
| <code>string</code> | $message  | Message body |
| <code>string</code> | $smileys  | Use smileys or not |
| <code>boolean</code> | $to_group  | Set to true if sending to the entire user group's members |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sendemail" class="anchor"></a>
####  sendemail() : boolean

```
 sendemail(string  $toname, string  $toemail, string  $fromname, string  $fromemail, string  $subject, string  $message, string  $type = &quot;html&quot;, string  $cc = &quot;&quot;, string  $bcc = &quot;&quot;) : boolean
```

**Summary**

Send email via PHPMailer Class

**Details:**
* File: [sendmail_include.php](files/sendmail_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $toname  | The name of the receiver. |
| <code>string</code> | $toemail  | The mail of the receiver. |
| <code>string</code> | $fromname  | Sender's name. |
| <code>string</code> | $fromemail  | Sender's email. |
| <code>string</code> | $subject  | Email subject. |
| <code>string</code> | $message  | Email message. |
| <code>string</code> | $type  | Text type. Possible value: text, html. |
| <code>string</code> | $cc  | Carbon copy, whom do you want to send copies of this mail to. |
| <code>string</code> | $bcc  | Blind carbon copy, this receiver will not be able to see from
                         whom this mail has been sent to others than the receiver. |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPMailer\PHPMailer\Exception |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sendemail_template" class="anchor"></a>
####  sendemail_template() : boolean

```
 sendemail_template(string  $template_key, string  $subject, string  $message, string  $user, string  $receiver, string  $thread_url, string  $toemail, string  $sender = &quot;&quot;, string  $fromemail = &quot;&quot;) : boolean
```

**Summary**

Send email with template

**Details:**
* File: [sendmail_include.php](files/sendmail_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $template_key  | Template key. |
| <code>string</code> | $subject  | Email subject. |
| <code>string</code> | $message  | Email message. |
| <code>string</code> | $user  | User name. |
| <code>string</code> | $receiver  | The name of the receiver. |
| <code>string</code> | $thread_url  | Forum thread url. |
| <code>string</code> | $toemail  | The mail of the receiver. |
| <code>string</code> | $sender  | Sender's name. |
| <code>string</code> | $fromemail  | Sender's email. |
##### Throws:
| Type | Description |
| ---- | ----------- |
| \PHPMailer\PHPMailer\Exception |  |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_server" class="anchor"></a>
####  server() : mixed

```
 server(string  $key, integer  $type = FILTER_DEFAULT) : mixed
```

**Summary**

Gets server array

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>integer</code> | $type  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_session_add" class="anchor"></a>
####  session_add() : mixed

```
 session_add(string  $key, mixed  $value) : mixed
```

**Summary**

Add a value to $_SESSION

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |
| <code>mixed</code> | $value  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_session_clean" class="anchor"></a>
####  session_clean() 

```
 session_clean() 
```

**Summary**

Cleans curent $_SESSION

**Details:**
* File: [defender.php](files/defender.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_session_get" class="anchor"></a>
####  session_get() : mixed

```
 session_get(string&amp;#124;array  $key) : mixed
```

**Summary**

Get session

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $key  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_session_remove" class="anchor"></a>
####  session_remove() : mixed

```
 session_remove(string  $key) : mixed
```

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $key  |  |

**Returns:** mixed

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_admin_pass" class="anchor"></a>
####  set_admin_pass() : boolean

```
 set_admin_pass(string  $password) : boolean
```

**Summary**

Set password of the currently logged in an administrator.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $password  | Any password. |

**Returns:** boolean - True if a password is set.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_error" class="anchor"></a>
####  set_error() 

```
 set_error(integer  $error_level, string  $error_message, string  $error_file, integer  $error_line) 
```

**Summary**

Custom Error Handler

**Details:**
* File: [error_handling_include.php](files/error_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $error_level  | Severity |
| <code>string</code> | $error_message  | $e->message |
| <code>string</code> | $error_file  | The file in question, run a debug_backtrace()[2] in the file |
| <code>integer</code> | $error_line  | The line in question, run a debug_backtrace()[2] in the file |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_fusion_field_config" class="anchor"></a>
####  set_fusion_field_config() 

```
 set_fusion_field_config(  $field_config) 
```

**Summary**

Sets field configurations

**Details:**
* File: [defender.php](files/defender.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $field_config  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_image" class="anchor"></a>
####  set_image() 

```
 set_image(string  $name, string  $path) 
```

**Summary**

Set a path of an image.

**Details:**
* File: [system_images.php](files/system_images.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  | The name of an already defined image whose location you want to change, or your own image. |
| <code>string</code> | $path  | The path to the image you are setting. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_language" class="anchor"></a>
####  set_language() 

```
 set_language(string  $lang) 
```

**Summary**

Set the requested language.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $lang  | The name of the language. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_meta" class="anchor"></a>
####  set_meta() 

```
 set_meta(string  $name, string  $content = &quot;&quot;) 
```

**Summary**

Set a meta tag by name

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $name  |  |
| <code>string</code> | $content  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_setting" class="anchor"></a>
####  set_setting() : boolean

```
 set_setting(string  $setting_name, string  $setting_value, string  $setting_inf) : boolean
```

**Summary**

Update a setting for the given infusion or create it if the setting does not exist.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $setting_name  | The name of the setting, must be unique for each infusion. |
| <code>string</code> | $setting_value  | The value of the setting. |
| <code>string</code> | $setting_inf  | The infusion name this setting belongs to. |

**Returns:** boolean - Returns true on successful update / insert or false on error.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_status_header" class="anchor"></a>
####  set_status_header() : boolean

```
 set_status_header(integer  $code = 200) : boolean
```

**Summary**

Set HTTP status header.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $code  | Status header code. |

**Returns:** boolean - Whether header was sent.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_theme" class="anchor"></a>
####  set_theme() 

```
 set_theme(string  $theme) 
```

**Summary**

Set a valid theme.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme  | The theme folder you want to set. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_set_title" class="anchor"></a>
####  set_title() 

```
 set_title(string  $title = &quot;&quot;) 
```

**Summary**

Set the new title of the page.

**Description**

Function will replace the title meta tag's content by the one specified by the $title argument.

**Details:**
* File: [output_handling_include.php](files/output_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $title  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_setError" class="anchor"></a>
#### (deprecated) -  setError() 

```
 setError(integer  $error_level, string  $error_message, string  $error_file, integer  $error_line) 
```

**Summary**

Custom Error Handler

**Deprecated**
Deprecateduse set_error()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $error_level  | Severity |
| <code>string</code> | $error_message  | $e->message |
| <code>string</code> | $error_file  | The file in question, run a debug_backtrace()[2] in the file |
| <code>integer</code> | $error_line  | The line in question, run a debug_backtrace()[2] in the file |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_setnotice" class="anchor"></a>
####  setnotice() 

```
 setnotice(string  $status, string  $value, string  $key = FUSION_SELF, boolean  $remove_after_access = TRUE) 
```

**Summary**

Sets a notice message for the whole group identified by the key provided, this will overwrite any other notices previously set

**Details:**
* File: [notify.php](files/notify.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $status  | The status of the message. |
| <code>string</code> | $value  | The message. |
| <code>string</code> | $key  | The key identifying a group holding notices, by default the page name in which the notice was set. |
| <code>boolean</code> | $remove_after_access  | Whether the notice should be automatically removed after it was displayed once.
                                    If set to false when getnotices() is called you have the option to keep the notice even after it was accesed. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showbanners" class="anchor"></a>
####  showbanners() : string

```
 showbanners(integer  $display = NULL) : string
```

**Summary**

Display the site banner you specify through the Banner settings.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $display  | Possible value: 1, 2. If empty it shows banner 1. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showbenchmark" class="anchor"></a>
####  showbenchmark() : string

```
 showbenchmark(boolean  $show_sql_performance = FALSE, string  $performance_threshold = &#039;0.01&#039;) : string
```

**Summary**

Show benchmark and database performance.

**Description**

Developer tools only (Translations not Required)

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $show_sql_performance  | True to pop up SQL analysis modal |
| <code>string</code> | $performance_threshold  | Results that is slower than this will be highlighted |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showcomments" class="anchor"></a>
####  showcomments() 

```
 showcomments(string  $comment_type, string  $comment_db, string  $comment_col, integer  $comment_item_id, string  $clink, boolean  $ratings = FALSE) 
```

**Summary**

Display a comments form.

**Details:**
* File: [comments_include.php](files/comments_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $comment_type  | The comment type you want to display. |
| <code>string</code> | $comment_db  | The database table where the item you want to comment on resides in. |
| <code>string</code> | $comment_col  | The field in the table which holds the id for the item you want to comment on. |
| <code>integer</code> | $comment_item_id  | The actual id to the item you are commenting on. |
| <code>string</code> | $clink  | The actual id to the item you are commenting on. |
| <code>boolean</code> | $ratings  | Display ratings. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showcopyright" class="anchor"></a>
####  showcopyright() : string

```
 showcopyright(string  $class = &quot;&quot;, false  $nobreak = FALSE) : string
```

**Summary**

Show the PHPFusion copyright.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $class  | The class attribute of the link. |
| <code>false</code> | $nobreak  | If true <br> tag will be removed between copyright and license. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showcounter" class="anchor"></a>
####  showcounter() : string

```
 showcounter() : string
```

**Summary**

If the visitor counter is enabled in settings this function will return the number of visitors.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showdate" class="anchor"></a>
####  showdate() : string

```
 showdate(string  $format, integer  $val, array  $options = array()) : string
```

**Summary**

Format the date and time according to the site and user offset.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $format  | Possible value: shortdate, longdate, forumdate, newsdate or date pattern for the strftime. |
| <code>integer</code> | $val  | Unix timestamp. |
| <code>array</code> | $options  | Possible options tz_override. |

**Returns:** string - String formatted according to the given format string.
               Month and weekday names and other language dependent strings respect the current locale set.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showfootererrors" class="anchor"></a>
####  showfootererrors() : null

```
 showfootererrors() : null
```

**Summary**

Return footer error notice

**Details:**
* File: [error_handling_include.php](files/error_handling_include.md)

**Returns:** null

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showlogo" class="anchor"></a>
####  showlogo() : string

```
 showlogo(string  $class = &#039;logo&#039;) : string
```

**Summary**

Show site logo.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $class  | CSS class. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showmemoryusage" class="anchor"></a>
####  showmemoryusage() : string

```
 showmemoryusage() : string
```

**Summary**

Show memory usage

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showprivacypolicy" class="anchor"></a>
####  showprivacypolicy() : string

```
 showprivacypolicy() : string
```

**Summary**

Show popup with privacy policy text.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showratings" class="anchor"></a>
####  showratings() 

```
 showratings(string  $rating_type, integer  $rating_item_id, string  $rating_link) 
```

**Summary**

Display a ratings form.

**Details:**
* File: [ratings_include.php](files/ratings_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $rating_type  | The rating type you want to display. |
| <code>integer</code> | $rating_item_id  | The item id you are rating. |
| <code>string</code> | $rating_link  | The link for the page which the rating is on. |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showrendertime" class="anchor"></a>
####  showrendertime() : string

```
 showrendertime(boolean  $queries = TRUE) : string
```

**Summary**

Show PHPFusion performance.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>boolean</code> | $queries  | Show the number of queries used on the current page. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showsubdate" class="anchor"></a>
#### (deprecated) -  showsubdate() : string

```
 showsubdate() : string
```

**Summary**

Show the current time often this code is used in theme subheader.

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_showsublinks" class="anchor"></a>
####  showsublinks() : string

```
 showsublinks(string  $sep = &quot;&quot;, string  $class = &quot;navbar-default&quot;, array  $options = array()) : string
```

**Summary**

Displays Site Links navigation bar.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $sep  | Separator between links. |
| <code>string</code> | $class  | CSS class of the navbar. |
| <code>array</code> | $options  | Notice: There is a more powerful method now that offers more powerful manipulation methods
that non oo approach cannot ever achieve using cache and the new mutator method
SiteLinks::setSubLinks($sep, $class, $options)->showsublinks(); for normal usage |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_social_media_links" class="anchor"></a>
####  social_media_links() : string

```
 social_media_links(string  $url, array  $options = array()) : string
```

**Summary**

Return a list of social media sharing services where an url can be shared.

**Description**

Requires the loading of Font Awesome which can be enabled in theme settings.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $url  | The URL to share. |
| <code>array</code> | $options  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sort_tree" class="anchor"></a>
####  sort_tree() : array

```
 sort_tree(array  $result, string  $key) : array
```

**Summary**

To sort key on dbtree_index() results.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $result  | dbtree_index() result. |
| <code>string</code> | $key  | Array key. |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_sorter" class="anchor"></a>
####  sorter() : array

```
 sorter(array  $array, string  $key, string  $sort = &#039;ASC&#039;) : array
```

**Summary**

Sort tree an associative array.

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |
| <code>string</code> | $key  |  |
| <code>string</code> | $sort  |  |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_string_to_color_code" class="anchor"></a>
####  string_to_color_code() : string

```
 string_to_color_code(string  $text) : string
```

**Summary**

Generate HEX color code from string.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | Any string. |

**Returns:** string - HEX color code.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_strip_bbcodes" class="anchor"></a>
####  strip_bbcodes() : string

```
 strip_bbcodes(string  $text) : string
```

**Summary**

Strip declared BBCodes and their content away from quoted messages.

**Details:**
* File: [bbcode_include.php](files/bbcode_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | A string containing text with bbcodes. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_stripfilename" class="anchor"></a>
####  stripfilename() : string

```
 stripfilename(string  $filename) : string
```

**Summary**

Strips a given filename from any unwanted characters and symbols.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $filename  | Filename you want to strip. Remember to remove the file extension before parsing it through this function. |

**Returns:** string - The filename stripped and ready for use.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_stripget" class="anchor"></a>
####  stripget() : boolean

```
 stripget(array&amp;#124;string  $check_url) : boolean
```

**Summary**

Prevent any possible XSS attacks via $_GET.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array&#124;string</code> | $check_url  | String or array to be stripped. |

**Returns:** boolean - True if the URL is not secure.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_stripinput" class="anchor"></a>
####  stripinput() : array&amp;#124;string

```
 stripinput(string&amp;#124;array  $text) : array&amp;#124;string
```

**Summary**

Prevents HTML in unwanted places

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string&#124;array</code> | $text  | String or array to be stripped. |

**Returns:** array&#124;string - The given string decoded as non HTML text.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_stripslash" class="anchor"></a>
#### (deprecated) -  stripslash() : string

```
 stripslash(string  $text) : string
```

**Summary**

Strip Slash Function, only stripslashes if magic_quotes_gpc is on.

**Deprecated**
Deprecateduse stripslashes()
**Details:**
* File: [deprecated.php](files/deprecated.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | The input string. |

**Returns:** string - String with backslashes stripped off (\' becomes ' and so on), double backslashes (\) are made into a single backslash (\).

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_strleft" class="anchor"></a>
####  strleft() : false&amp;#124;string

```
 strleft(  $s1,   $s2) : false&amp;#124;string
```

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $s1  |  |
| <code></code> | $s2  |  |

**Returns:** false&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_suspend_log" class="anchor"></a>
####  suspend_log() 

```
 suspend_log(integer  $user_id, integer  $type, string  $reason = &quot;&quot;, false  $system = FALSE, boolean  $time = TRUE) 
```

**Summary**

Save suspendation to log.

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |
| <code>integer</code> | $type  |  |
| <code>string</code> | $reason  |  |
| <code>false</code> | $system  |  |
| <code>boolean</code> | $time  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_tab_active" class="anchor"></a>
####  tab_active() : string

```
 tab_active(array  $array, integer  $default_active, string  $getname = NULL) : string
```

**Summary**

Current active tab selector.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  | Multidimension array consisting of keys title, id, icon. |
| <code>integer</code> | $default_active  | 0 if link_mode is false, $_GET if link_mode is true. |
| <code>string</code> | $getname  | Set getname and turn tabs into link that listens to getname. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_tab_index" class="anchor"></a>
####  tab_index() : integer

```
 tab_index(array  $array, string  $default_active, boolean  $getname = FALSE) : integer
```

**Summary**

Get current active tab index

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $array  |  |
| <code>string</code> | $default_active  |  |
| <code>boolean</code> | $getname  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_tablebreak" class="anchor"></a>
#### (deprecated) -  tablebreak() 

```
 tablebreak() 
```

**Deprecated**
Deprecated
**Details:**
* File: [deprecated.php](files/deprecated.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_theme_exists" class="anchor"></a>
####  theme_exists() : boolean

```
 theme_exists(string  $theme) : boolean
```

**Summary**

Check if a given theme exists and is valid.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $theme  | The theme folder you want to check. |

**Returns:** boolean - False if the theme does not exist and true if it does.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_thumbnail" class="anchor"></a>
####  thumbnail() : string

```
 thumbnail(string  $src, string  $size, boolean  $url = FALSE, boolean  $colorbox = FALSE, boolean  $responsive = TRUE, string  $class = &quot;m-2&quot;) : string
```

**Summary**

Show image thumbnail.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $src  | The path to image. |
| <code>string</code> | $size  | Image size. |
| <code>boolean</code> | $url  | Make image clickable. |
| <code>boolean</code> | $colorbox  | Allow colorbox(). |
| <code>boolean</code> | $responsive  | Add img-responsive class. |
| <code>string</code> | $class  | CSS class. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_timer" class="anchor"></a>
####  timer() : string

```
 timer(integer  $time = NULL) : string
```

**Summary**

Show time ago from timestamp.

**Details:**
* File: [theme_functions_include.php](files/theme_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $time  | Timestamp or if empty it use time(). |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_translate_country_names" class="anchor"></a>
####  translate_country_names() : string

```
 translate_country_names(  $country) : string
```

**Summary**

Given English as base, find out the localized version.

**Details:**
* File: [translate_include.php](files/translate_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $country  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_translate_lang_names" class="anchor"></a>
####  translate_lang_names() : array&amp;#124;string

```
 translate_lang_names(string  $language) : array&amp;#124;string
```

**Summary**

Translate locale folder name into localized language.

**Details:**
* File: [translate_include.php](files/translate_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $language  |  |

**Returns:** array&#124;string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_tree_count" class="anchor"></a>
####  tree_count() : integer

```
 tree_count(array  $data, boolean  $column_name = NULL, boolean  $value_to_match = NULL) : integer
```

**Summary**

Count result from dbquery_tree().

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | Results from dbquery_tree(). |
| <code>boolean</code> | $column_name  | Column name. |
| <code>boolean</code> | $value_to_match  | Value to match. |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |
| todo |  | : Change to count on index in favor of deprecated method
     Get the occurences of a column name matching value
     $unpublish_count = tree_count($dbtree_result, "column_name", "value")-1; |

<a name="method_tree_depth" class="anchor"></a>
####  tree_depth() : integer

```
 tree_depth(array  $data, string  $field, string  $match, integer  $depth = 1) : integer
```

**Summary**

Get the total max depths of dbtree().

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | Results from dbtree(). |
| <code>string</code> | $field  |  |
| <code>string</code> | $match  |  |
| <code>integer</code> | $depth  |  |

**Returns:** integer

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_tree_index" class="anchor"></a>
####  tree_index() : array

```
 tree_index(array  $data) : array
```

**Summary**

Get index information from dbquery_tree_full().

**Details:**
* File: [sqlhandler.inc.php](files/sqlhandler.inc.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>array</code> | $data  | Array generated from dbquery_tree_full(). |

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_trim_text" class="anchor"></a>
####  trim_text() : string

```
 trim_text(string  $str, integer  $length = 300) : string
```

**Summary**

Pure trim function.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $str  | String to trim. |
| <code>integer</code> | $length  | The number of characters. |

**Returns:** string - Trimmed text.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_trimlink" class="anchor"></a>
####  trimlink() : string

```
 trimlink(string  $text, integer  $length) : string
```

**Summary**

Prevent strings from growing to long and breaking the layout.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $text  | String to trim. |
| <code>integer</code> | $length  | Max length of the string. |

**Returns:** string - String trimmed to the given length.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_uncompressipv6" class="anchor"></a>
####  uncompressipv6() : string

```
 uncompressipv6(string  $ip, integer  $count = 7) : string
```

**Summary**

Convert a shortened IPv6 address to its full length form.

**Details:**
* File: [ip_handling_include.php](files/ip_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $ip  | IPv6 address to convert. |
| <code>integer</code> | $count  | This parameter shows how many : are in the full length version.
                     Note: IPv6 address has 7 of them, but the mixed (IPv6 and IPv4) address has only 5. |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_unsuspend_log" class="anchor"></a>
####  unsuspend_log() 

```
 unsuspend_log(integer  $user_id, integer  $type, string  $reason = &quot;&quot;, boolean  $system = FALSE) 
```

**Summary**

Unsuspend user.

**Details:**
* File: [suspend_include.php](files/suspend_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  |  |
| <code>integer</code> | $type  |  |
| <code>string</code> | $reason  |  |
| <code>boolean</code> | $system  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_upload_file" class="anchor"></a>
####  upload_file() : array

```
 upload_file(string  $source_file, string  $target_file = &quot;&quot;, string  $target_folder = DOWNLOADS, string  $valid_ext = &quot;.zip,.rar,.tar,.bz2,.7z&quot;, integer  $max_size = 15000, string  $query = &quot;&quot;, false  $replace_upload = FALSE) : array
```

**Summary**

File uploading.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source_file  | The key of the $_FILE which holds the uploaded file. |
| <code>string</code> | $target_file  | Name for the uploaded file, leave this blank to use the uploaded file's name. |
| <code>string</code> | $target_folder  | Folder the uploaded file will be moved to. |
| <code>string</code> | $valid_ext  | Valid file extensions for uploaded files. |
| <code>integer</code> | $max_size  | Maximum allowed file size. |
| <code>string</code> | $query  | DB Query when the file is uploaded. |
| <code>false</code> | $replace_upload  | Replace the file if exists in the target folder. |

**Returns:** array - Array with information about the upload.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_upload_image" class="anchor"></a>
####  upload_image() : array

```
 upload_image(string  $source_image, string  $target_name = &quot;&quot;, string  $target_folder = IMAGES, integer  $target_width = 1800, integer  $target_height = 1600, integer  $max_size = 150000, false  $delete_original = FALSE, boolean  $thumb1 = TRUE, boolean  $thumb2 = TRUE, integer  $thumb1_ratio, string  $thumb1_folder = IMAGES, string  $thumb1_suffix = &quot;_t1&quot;, integer  $thumb1_width = 100, integer  $thumb1_height = 100, integer  $thumb2_ratio, string  $thumb2_folder = IMAGES, string  $thumb2_suffix = &quot;_t2&quot;, integer  $thumb2_width = 400, integer  $thumb2_height = 300, string  $query = &quot;&quot;, array  $allowed_extensions = array(&#039;.jpg&#039;, &#039;.jpeg&#039;, &#039;.png&#039;, &#039;.png&#039;, &#039;.svg&#039;, &#039;.gif&#039;, &#039;.bmp&#039;), false  $replace_upload = FALSE) : array
```

**Summary**

Image uploading.

**Details:**
* File: [infusions_include.php](files/infusions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $source_image  | Key for the uploaded file in the $_FILES[] array. |
| <code>string</code> | $target_name  | Name of the uploaded image, leave this blank to use the original image name. |
| <code>string</code> | $target_folder  | The folder you are uploading the image to. |
| <code>integer</code> | $target_width  | Maximum allowed width of image in pixels. |
| <code>integer</code> | $target_height  | Maximum allowed height of image in pixels. |
| <code>integer</code> | $max_size  | Max size of image in bytes. |
| <code>false</code> | $delete_original  | Set this to true if you wish the original image to be delete after upload. |
| <code>boolean</code> | $thumb1  | Set this to true if you wish to generate a thumbnail number 1. |
| <code>boolean</code> | $thumb2  | Set this to true if you wish to generate a thumbnail number 2. |
| <code>integer</code> | $thumb1_ratio  | Image ratio for the first thumbnail. 0 means original image ratio, 1 means square image ratio. |
| <code>string</code> | $thumb1_folder  | Folder for the first thumbnail. |
| <code>string</code> | $thumb1_suffix  | Text which will be appended at the end of the image name of the first thumbnail. |
| <code>integer</code> | $thumb1_width  | Width of first thumbnail in pixels. |
| <code>integer</code> | $thumb1_height  | Height of first thumbnail in pixels. |
| <code>integer</code> | $thumb2_ratio  | Image ratio for the second thumbnail. 0 means original image ratio, 1 means square image ratio. |
| <code>string</code> | $thumb2_folder  | Folder for the second thumbnail. |
| <code>string</code> | $thumb2_suffix  | Text which will be appended at the end of the image name of the second thumbnail. |
| <code>integer</code> | $thumb2_width  | Width of second thumbnail in pixels. |
| <code>integer</code> | $thumb2_height  | Height of first thumbnail in pixels. |
| <code>string</code> | $query  | DB Query when the image is uploaded. |
| <code>array</code> | $allowed_extensions  | Allowed image extensions. |
| <code>false</code> | $replace_upload  | Replace image if exists in the target folder. |

**Returns:** array - Array with information about the upload.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_user_blacklisted" class="anchor"></a>
####  user_blacklisted() : boolean

```
 user_blacklisted(integer  $user_id) : boolean
```

**Summary**

Check if user was blacklisted by a member.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  | User ID. |

**Returns:** boolean - True if the user is blacklisted.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_user_pm_settings" class="anchor"></a>
####  user_pm_settings() : array&amp;#124;string

```
 user_pm_settings(integer  $user_id, string  $key = NULL) : array&amp;#124;string
```

**Summary**

Fetch user PM settings.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $user_id  | User ID. |
| <code>string</code> | $key  | user_inbox, user_outbox, user_archive, user_pm_email_notify, user_pm_save_sent |

**Returns:** array&#124;string - Associative array of all data or one column by key.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_user_search" class="anchor"></a>
####  user_search() 

```
 user_search(  $user_id) 
```

**Details:**
* File: [dynamics\includes\form_select.php](files/dynamics.includes.form_select.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $user_id  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | dynamics/select2 |

<a name="method_users_groupaccess" class="anchor"></a>
####  users_groupaccess() : boolean

```
 users_groupaccess(integer  $group_id) : boolean
```

**Summary**

Check if user has access to the group.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>integer</code> | $group_id  | The ID of the group. |

**Returns:** boolean - True if the user has access.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_valid_language" class="anchor"></a>
####  valid_language() : boolean

```
 valid_language(string  $lang, boolean  $file_check = FALSE) : boolean
```

**Summary**

Check if a given language is valid or if exists.

**Description**

Checks whether a language can be found in enabled languages array.
Can also be used to check whether a language actually exists.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $lang  | The name of the language. |
| <code>boolean</code> | $file_check  | Intended to be used when enabling languages in Admin Panel. |

**Returns:** boolean

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_verify_image" class="anchor"></a>
####  verify_image() : boolean

```
 verify_image(string  $file) : boolean
```

**Summary**

Scan image files for malicious code.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $file  | Path to image. |

**Returns:** boolean - True or false, depending on whether the image is safe or not.

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_video_mimetypes" class="anchor"></a>
####  video_mimetypes() : array

```
 video_mimetypes() : array
```

**Summary**

Array of video mime types.

**Details:**
* File: [mimetypes_include.php](files/mimetypes_include.md)

**Returns:** array

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_whitespace" class="anchor"></a>
####  whitespace() : string

```
 whitespace(  $value) : string
```

**Summary**

Adds a whitespace if value is present.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code></code> | $value  |  |

**Returns:** string

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_write_error" class="anchor"></a>
####  write_error() 

```
 write_error(string  $error_message, string  $error_file, integer  $error_line) 
```

**Summary**

Write error to file

**Details:**
* File: [error_handling_include.php](files/error_handling_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $error_message  |  |
| <code>string</code> | $error_file  |  |
| <code>integer</code> | $error_line  |  |



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_write_file" class="anchor"></a>
####  write_file() : integer

```
 write_file(string  $file, string&amp;#124;array  $data, integer  $flags = NULL) : integer
```

**Summary**

A wrapper function for file_put_contents with cache invalidation.

**Description**

If opcache is enabled on the server, this function will write the file.
as the original file_put_contents and invalidate the cache of the file.
It is needed when you create a file dynamically and want to include it
before the cache is invalidated. Redirection does not matter.

**Details:**
* File: [core_functions_include.php](files/core_functions_include.md)
##### Parameters:
| Type | Name | Description |
| ---- | ---- | ----------- |
| <code>string</code> | $file  | File path. |
| <code>string&#124;array</code> | $data  | The data to write. |
| <code>integer</code> | $flags  |  |

**Returns:** integer - Number of written bytes

##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_write_htaccess" class="anchor"></a>
####  write_htaccess() 

```
 write_htaccess() 
```

**Summary**

Generate .htaccess file

**Details:**
* File: [htaccess_include.php](files/htaccess_include.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_xusername_validation" class="anchor"></a>
####  xusername_validation() 

```
 xusername_validation() 
```

**Summary**

Username validation

**Details:**
* File: [api\username_validation.php](files/api.username_validation.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |

<a name="method_xuserpass_validation" class="anchor"></a>
####  xuserpass_validation() 

```
 xuserpass_validation() 
```

**Summary**

Validate password strength

**Details:**
* File: [api\userpass_validation.php](files/api.userpass_validation.md)



##### Tags
| Tag | Version | Description |
| --- | ------- | ----------- |
| package |  | Default |


---

### Top Namespaces

* [\Defender](namespaces/Defender.html.md)
* [\PHPFusion](namespaces/PHPFusion.html.md)

---

### Reports
* [Errors - 1023](reports/errors.md)
* [Markers - 6](reports/markers.md)
* [Deprecated - 36](reports/deprecated.md)

---

This document was automatically generated from source code comments on 2021-07-21 using [phpDocumentor](http://www.phpdoc.org/) and [fr3nch13/phpdoc-markdown](https://github.com/fr3nch13/phpdoc-markdown)
