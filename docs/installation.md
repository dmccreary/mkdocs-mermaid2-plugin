# Installing the Mermaid2 Plugin

## Pip install method

```sh
pip3 install mkdocs-mermaid2-plugin
```

### Successfully Installed Message

```
Installing collected packages: urllib3, soupsieve, idna, editorconfig, chardet, requests, jsbeautifier, beautifulsoup4, mkdocs-mermaid2-plugin
Successfully installed beautifulsoup4-4.9.3 chardet-4.0.0 editorconfig-0.12.3 idna-2.10 jsbeautifier-1.13.5 mkdocs-mermaid2-plugin-0.5.1 requests-2.25.1 soupsieve-2.2 urllib3-1.26.3
```

### Successful build messages

```
$ mkdocs serve
INFO    -  Building documentation... 
INFO    -  MERMAID2  - Initialization arguments: {} 
INFO    -  MERMAID2  - Using javascript library (8.8.0):
   https://unpkg.com/mermaid@8.8.0/dist/mermaid.min.js 
```

## Common Errors
$ mkdocs serve
INFO    -  Building documentation... 
ERROR   -  Config value: 'plugins'. Error: The "mermaid2" plugin is not installed 

The python mkdocs system could not find the mermaid2 plugin.

Check you conda environment.