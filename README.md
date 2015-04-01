# openlayers3
This is openlayers3 production package.

If you want to use this within Symfony, you need to add the follow configuration to your _config.yml_

```yml
assetic:
  assets:
    openlayers3:
      inputs:
        - %kernel.root_dir%/../vendor/ohvitorino/openlayers3/ol.js
    openlayers3_css:
      inputs:
        - %kernel.root_dir%/../vendor/ohvitorino/openlayers3/ol.css
```
