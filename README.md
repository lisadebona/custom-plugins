# WordPress Plugins & Snippets

This repository is a working collection of **WordPress plugins** and **useful snippets for website development**. Each plugin lives in its own folder and can be dropped into `/wp-content/plugins/`, while snippets are small, self-contained pieces of code meant to be copied into a theme, a child theme, or a site-specific plugin.

## What's here

| Path | Description |
| --- | --- |
| [`mysite-mail-smtp/`](mysite-mail-smtp/) | WordPress plugin that routes `wp_mail()` through PHP Mail, the Gmail API (OAuth 2.0), or Microsoft 365 SMTP. Includes a settings screen and an email test tab. |

More plugins and snippets will be added over time, so the layout may change as the collection grows.

## Using a plugin

1. Copy the plugin folder into `wp-content/plugins/` on your site.
2. Activate it from **Plugins** in the WordPress admin.
3. Follow the plugin's own `readme.txt` for configuration and setup details.

Every plugin folder includes its own `readme.txt` with requirements, installation steps, and a changelog.

## Using a snippet

Snippets are provided as reference code rather than installable packages. Before using one:

- Read through it and adjust names, prefixes, and settings to match your site.
- Add it to a **child theme's `functions.php`** or, preferably, a small site-specific plugin so it survives theme updates.
- Test on a staging site first — snippets can affect the whole site.

## Requirements

WordPress plugins here generally target **WordPress 5.5+** and **PHP 7.4+** unless a plugin's `readme.txt` says otherwise. Check the individual plugin's readme for exact versions.

## License

Unless stated otherwise in a plugin folder, code in this repository is licensed under the **GPLv3 or later**, matching WordPress itself.
