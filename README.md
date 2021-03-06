## My Sublime Text 3 Settings
###### May 1, 2016

This is as much for my reference as it is to share with whoever finds it helpful. My setup is focused on frontend development and workflow enhancements. Designers who develop (like me) are most likely to find this setup handy. Let me know if you like it :)

##### Install these packages...

Start with [PackageControl](https://packagecontrol.io/installation) _of course_...  
[Auto​File​Name](https://packagecontrol.io/packages/AutoFileName)  
[BracketHighlighter](https://packagecontrol.io/packages/BracketHighlighter)  
[Color Highlighter](https://packagecontrol.io/packages/Color%20Highlighter)  
[Color​Picker](https://packagecontrol.io/packages/ColorPicker)  
[CSS3](https://packagecontrol.io/packages/CSS3)  
[CSS Extended Completions](https://packagecontrol.io/packages/CSS%20Extended%20Completions)  
[j​Query](https://packagecontrol.io/packages/jQuery)  
[JsFormat](https://packagecontrol.io/packages/JsFormat)  
[LESS](https://packagecontrol.io/packages/LESS)  
[Sass](https://packagecontrol.io/packages/Sass)  
[Sidebar Enhancements](https://packagecontrol.io/packages/SideBarEnhancements)  
[SublimeLinter](https://packagecontrol.io/packages/SublimeLinter) _Linters must be installed separately._ [Read the docs](https://sublimelinter.readthedocs.io/en/latest/)  
[Theme - SoDaReloaded](https://packagecontrol.io/packages/Theme%20-%20SoDaReloaded)  
[TrailingSpaces](https://packagecontrol.io/packages/TrailingSpaces)

##### ...then copy/paste my settings into `Preferences -> Settings - User`

```json
{
    "color_scheme": "Packages/User/SublimeLinter/Monokai (SL).tmTheme",
    "font_size": 14,
    "ignored_packages":
    [
        "Vintage"
    ],
    "theme": "SoDaReloaded Dark.sublime-theme",
    "tab_size": 4,
    "translate_tabs_to_spaces": true,
    "word_separators": "./\\()\"':,.;<>~!@#$%^&*|+=[]{}`~?",
    "word_wrap": "true"

}
```