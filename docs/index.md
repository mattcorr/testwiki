# Welcome to MkDocs

For full documentation visit [mkdocs.org](https://www.mkdocs.org).

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout


```
mkdocs.yml    # The configuration file.
docs/
    index.md  # The documentation homepage.
    ...       # Other markdown pages, images and other files.
```

### test Section

This is a new section with some code

to enter code view use ++ctrl+end+del++ key we can go to [here](about.md#Fubar).

```powershell
Write-Host "This is a sample" -NoNewLine
# This is a comment
$variable = "this is a $($test-1)"
```

It handles all **types** of `Write-Host "formattings"` and *stuff*.

This is the sort of thing it can write

Some **yaml** code:

```yaml
site_name: DevOps Knowledge Base
site_url: https://devops.moqdigital.com
nav:
    - Home: index.md
    - About: about.md
theme: 
    name: mkdocs
    locale: en
    highlightjs: true
    hljs_languages:
        - yaml
        - powershell
        - xml
        - json
```

!!!info
    This is a sample info box.
    Now look how good it is.

!!!warning "NOTE: Pay attention here"
    This is a sample warning box.
    Now look how good it is.

As you can see this is useful for us to test.

|Col1|Col2|Col3|
|---|---|---|
|Data1|Data2|data3|
|Data1|Data2|data3|
|Data1|Data2|data3|
|Data1|Data2|data3|
|Data1|Data2|data3|
|Data1|Data2|data3|

### More Data

More stuff goes **here**.