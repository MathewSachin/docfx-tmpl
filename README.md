# docfx-tmpl
DocFX Template

Supported DocFX version: 2.17.4

How to use:

In docfx.json (showing only relevant portion):

```json
{
    "build": {
        "template": [
            "default",
            "<relative path to src folder of this template>"
        ]
    }
}
```