# Neo-Zen

Reasons behind this rewrite:

- **First reason:** Need a way to make it work with noctalia and matugen, giving the options to change the colors without having to edit the CSS file.

- **Second reason:** I'll no longer use anything from any other theme. In the last rewrite, animations from the Nebula theme were removed—why? Well, it was causing some problems. This time I'm removing transparent settings and the better PDF features from Green's theme (or whatever it was called).

- **Third reason:** Zen is adding features, changing things, and breaking things. Because of this, the only things really worth changing are the colors, the footer area, and maybe the findbar. It's just not worth creating a fully interconnected theme where changing a setting causes the entire theme to adapt to it. Also, I tried to make a new options organization in the last rewrite, but it doesn't adapt to the changes related to the noctalia implementation. That's why I never updated the options in the wiki and the `theme.json`. I'm sorry for that; this time I'll add the options to `theme.json` once I complete a specific part, and I'll update the wiki with the new options.

- **Fourth reason:** Lightweight, without using JavaScript. Well, """"""lightweight"""""" in quotes because maybe I'll end up using a ton of variables in the CSS, and in some cases, that causes some lag.

- **Fifth reason:** NO, THAT'S NOT A FORK OF ANY OTHER THEME! Neo Zen is an independent theme. It's not a fork of any other theme; it's a completely different theme with its own features and options.

- **Sixth reason:** Maybe... just maybe... I'll make a script to automatically add the templates to matugen and noctalia.

- **Seventh reason:** I forgot this one for a moment, THE THEME IS UGLY AS HELL WHEN using it in light mode. Why?, well, the "glow" effect just looks good when using the theme in dark mode, how can I fix this?, using light-dark() in the CSS variables, that way the glow effect will be there only on dark mode, meanwhile, in light mode there will be only a shadow effect; Another problem is the opacity of the shadow, the glow effect needs to use a higher opacity and also a filter, so... to fix that... :l i don't fkn know how i'll do that yet because the size of the filters and shadows are different between modes and elements... so I'm fked up.

- **Eighth reason:** It is part of the seventh reason, maybe I'll try to make it look like glass in light mode... MAYBE. With the first commits in this branch, you can test the opacity of the browser background changing the values between 0 and 100 using the options neo.options.opacity.browser.background and neo.options.opacity.browser.tab.background, so you can get a full transparent browser... well on linux and macOS, on windows you have to pray for 3rd party programs to get a better effect than the default "acrylic" effect" like mica for everyone or something like that.

The feature called "Neo ColorFixer" will be split into the entire theme, what I need with this is to make each part work separately, for example, color fixer overrides the color of the text and icons, but with this version you will be able to change the color of the text and icons for the tabs with any color from templates without affecting the rest of the elements like the url bar.

This will be completely integrated in the main branch when the integration of noctalia is complete, for matugen, it will be the same I just don't have a template for it yet.
