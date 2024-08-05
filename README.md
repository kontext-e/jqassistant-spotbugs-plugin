# jQAssistant Spotbugs Plugin

This is a plugin for jQAssistant that scans spotbugs reports. This is the continuation of the project previously maintained at [github.com/kontext-e/jqassistant-plugins](https://github.com/kontext-e/jqassistant-plugins).

For a documentation of this plugin see [spotbugs.adoc](src/main/asciidoc/spotbugs.adoc)

## How to install
### jQAssistant 1.12+

Use the jqassistant.yaml as described [here](https://jqassistant.github.io/jqassistant/current/) and add the following 3 lines in the plugins section:

```
    - group-id: de.kontext-e.jqassistant.plugin
      artifact-id: jqassistant.plugin.spotbugs
      version: 2.1.0
```

### Prior to jQAssistant 1.12

Download the desired version from maven (e.g. [here](https://mvnrepository.com/artifact/de.kontext-e.jqassistant.plugin/jqassistant.plugin.spotbugs)) and put the jar in the jqassistant plugins directory.