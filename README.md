# Quote Tool for Editor.js
This block-level tool for Editor.js allows you to add quotes to your articles.

# Usage
Add the Quote Tool to the `tools` property of your Editor.js `config` parameters.

```javascript
var config = {
    tools: {
        quote: {
            class: Quote,
            inlineToolbar: true //optional
        }
        //other tools
    }
    //other config params
};
```
