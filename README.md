# OpenLayers3
This is OpenLayers3 production package.

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

Another way to add OpenLayers3 to your project is to use the ```component-dir```
option. The ```component-dir``` option specifies the place to install 
OpenLayers3 for example in Symfony under web/assets.

To use this you'll need to add the following to your root composer.json:
```
{
    "require": {
            "robloach/component-installer": "*"
    },
    "config": {
        "component-dir": "web/assets"
    }
}
```