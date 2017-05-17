# docfx-tmpl
A DocFX Template patching the Default template.

Supported DocFX version: [v2.17.4](https://github.com/dotnet/docfx/releases/tag/v2.17.4)

## Changes from Default Template
- Full Width (uses container-fluid instead of container).
- Affix sidebar styled like Bootstrap Documentation.
- Thinner TOC toggle button on mobiles.
- Hides the **IN THIS ARTICLE** heading above sidebar.
- Tabular views for Namespace and enum pages.
- Pretty tables for Class view.
- Collapsible sections in API documentation.
- Round Buttons for View-Source and Edit.

## How to use

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