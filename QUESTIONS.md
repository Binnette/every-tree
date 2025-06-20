- What should be the width and height of the `mode` icon. I tried a lot of sizes for my SVG, seems like 19px is fine.
- In plugin `cycling_infra v2`, a `cycling` mode with type `entrances`is defined. It uses `markers` attribute that id not [documented](https://every-door.app/plugins/metadata/modes/#entrances), can you please add it?
- In the [documentation](https://every-door.app/plugins/metadata/modes/#entrances) for `entrances` mode, `rendering` attribute is documented and seems to do the same as `markers`. Was the `rendering` renamed to `markers`?
- I found a `bug`. To reproduce: install a plugin with errors (it will install be not activate), then remove the plugin. Go back to main screen, I still can see the tree icon of my entrance mode defined in my plugin.
- Another `bug` none of my translations from `fr.yaml are applied. My phone is in french and the inside app setting is also french.
- Since I defined a lot of presets and for example the preset `🟣 fig` which is a `natural=tree` and `species=Ficus carica`. I was hopping, that after create `🟣 fig` POI, that the title of the edit windows will be `🟣 fig` and not the classic `Tree`. I guess the default preset `Tree` for `natural=tree` is **stronger** that my `🟣 fig` preset. Is it intended or a bug?
- I tried to make a matcher for `natural=tree` and `species=Ficus carica` to display my custom `fig.svg` icon, but I didn't succeed. Can you please review my `plugin.yaml`?

- While installing a 404 not found plugin. EveryDoor should show error "plugin not found" instead of a zip extract error.