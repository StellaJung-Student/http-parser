# Http-parser

## This is a simple program to parse urls to check their status

### Node, Request, chalk are used for this project

**Install**

```
  1. Global mode
    npm install -g https://github.com/StellaJung-Student/http-parser
    http-parser -f urls.txt
    Or
    npm install https://github.com/StellaJung-Student/http-parser
    npx http-parser -f urls.txt

  2. Local mode
    npm intall
    node index.js -f urls.txt
```

**How can I use**

```
    1. default
    > http-parser -f urls.txt or node index.js -f urls.txt
    > http-parser -f urls1.txt -f urls2.html or node index.js -f urls1.txt -f urls2.html

    2. With timeout [ms]
    > http-parser -f urls.txt -t 5000 or node index.js -f urls.txt -t 5000

    3. With filter
    > http-parser -f urls.txt --good
    > http-parser -f urls.txt --bad
    > http-parser -f urls.txt --all cf) --all is default
    
    4. version check
    > http-parser -v or http-parser --version
```

**Color Desription**

- Status
  - 200 : Green
  - 400 or 404 : Red
  - Others : Grey
