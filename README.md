# U.S. Naval War College ASpace PUI

Created by @alexduryee for US Naval Historical Collection Archives.
Compatible with ArchivesSpace 2.7.1

## New Features

- Customization of header image, favicon, footer/welcome text, and color scheme
- Addition of a new Digital Object sort (Identifier)

## Using the Plugin

Add `"usnwc-aspace"` to the array in `AppConfig[:plugins]` in your `config/config.rb`

To use the custom header image, add the following line to `config/config.rb`:
`AppConfig[:pui_branding_img] = '/assets/images/Hattendorf_Historical_Center_Dept_Wordmark_Horz_FullColorB.png'`


## Customizing the Plugin

Changes to the PUI's color scheme can be made by editing `public/assets/stylesheets/usnwc_lib.css`

Welcome text can be edited by changing locale values in `public/locales/en.yml`

Footer text can be edited by changing text in `public/views/shared/footer.html.erb`
