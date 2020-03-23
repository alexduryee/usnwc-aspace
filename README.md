# U.S. Naval War College ASpace PUI

Created by @alexduryee for US Naval Historical Collection Archives.

## New Features

- Customization of header image, favicon, footer/welcome text, and color scheme
- Addition of a new Digital Object sort (Identifier)

## Using the Plugin

Add `"usnwc-aspace"` to the array in `AppConfig[:plugins]` in your `config/config.rb`

## Customizing the Plugin

Changes to the PUI's color scheme can be made by editing `public/assets/stylesheets/usnwc_lib.css`

Welcome text can be edited by changing locale values in `public/locales/en.yml`

Footer text can be edited by changing text in `public/views/shared/footer.html.erb`
