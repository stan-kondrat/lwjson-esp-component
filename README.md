# Lightweight JSON text parser - ESP IDF Component

Library provides generic JSON text parser, that is optimized for embedded systems. 

Source code https://github.com/MaJerle/lwjson

## Install 

1. Add **semver** dependency to **idf_component.yml**
```yml
dependencies:
  idf:
    version: ">=5"
  semver:
    path: .
    git: ssh://git@github.com/stan-kondrat/lwjson-esp-component.git
```

2. Reconfigure project
```sh
idf.py reconfigure
```

##  Documentation

http://docs.majerle.eu/projects/lwjson/

## License

MIT
