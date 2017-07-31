## React transform
    $ npm install -g babel-cli                               # 
    $ npm install --save-dev babel-cli babel-preset-react babel-preset-es2015  # for num run

### Using babel to transform all jsx files under folder "src" into js and put them to folder "static" 
    $ babel src --presets react,es2015 --out-dir static
    or 
    $ node_modules/.bin/babel src --presets react,es2015 --out-dir static
    
### use npm script
    "scripts": {
        "compile": "babel src --presets react,es2015 --out-dir static",
        "watch": "babel src --presets react,es2015 --out-dir static --watch"
    }
    $ npm run compile