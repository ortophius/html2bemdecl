# html2bemdecl
A very simple wrapper for html2bemjson and bemjson-to-decl modules.

## Usage
Just add a rule to `module`, like this:

 ```javascript
     module: {
        rules: [
            { test: /\.html$/, loader: "html2bemdecl-loader" }
        ]
    }
   ```
