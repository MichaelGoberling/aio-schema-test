# aio-schema-test
Test for aio schemas

# VSCode

## Pre-requisites 

- Install `YAML` extension

## Configure

- Preferences > Settings > Search `yaml schemas` > Click `Edit in settings.json`
- Add the following to `yaml.schemas`:
```
        "https://raw.githubusercontent.com/MichaelGoberling/aio-schema-test/main/aio.app.config.yaml.schema.json": [
            "app.config.yaml"
        ],
        "https://raw.githubusercontent.com/MichaelGoberling/aio-schema-test/main/aio.ext.config.yaml.schema.json": [
            "ext.config.yaml"
        ]
```
- Reload VSCode
