# Cron Expression Input

[![MIT License](https://img.shields.io/apm/l/atomic-design-ui.svg?)](https://github.com/JossyDevers/transpiler-js/blob/master/LICENSE) 
[![GitHub Release](https://img.shields.io/github/v/release/jossydevers/transpiler-js)]()

## Component

<div>
  <p>Cron UI: input component to generate cron expressions easily and intuitively, as in (crontab guru)[https://crontab.guru/]</p><br />
  <img src="https://i.ibb.co/RPbhw7K/cron-expression-input.png" alt="cron-expression-input" border="0">
  <img src="https://i.ibb.co/64SNsjW/cron-expression-input-editor.png" alt="cron-expression-input-editor" border="0">
</div>

### Usage

```yaml
    <!DOCTYPE html>
    <html>
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Sample Page</title>
    </head>
    <body>
        <!-- Component -->
        <cron-expression-input color="d58512"></cron-expression-input>
        <!-- Component -->
        <script src="cron-expression-input.js"></script>
    </body>
    </html>
```

<h2 align="center">Component Attributes</h2>

You can pass various attributes to the component to modify its behavior, Example with color attribute: <cron-expression-input color="#d58512"></cron-expression-input>

|Name|Type|Default|Description|
|:--:|:--:|:-----:|:----------|
|**`width`**|`{String}`|`100%`|The width of the component input|
|**`height`**|`{String}`|`34px`|The height of the component input|
|**`color`**|`{String}`|`#d58512`|The main color that the component elements will take|

### Thanks
* [@TheCloudConnectors](https://github.com/TheCloudConnectors), For your npm package to validate the structure of a cron expression [cron-validator](https://github.com/TheCloudConnectors/cron-validator).
* [@bamotav](https://github.com/bamotav), For the idea of ​​creating this web component.