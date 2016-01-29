## Usage

```bash
git clone git@github.com:cirias/node-es6-template.git
mv node-es6-template myproject
cd myproject
rm -r .git

npm install

# start directly
node index.js

# build
npm run build

# run build
npm run start

# clean build
npm run clean
```

## ESLint

Install eslint and style config.
```bash
npm install -g eslint eslint-config-airbnb
```

Configure for [vim syntastic](https://github.com/scrooloose/syntastic)
```viml
let g:syntastic_javascript_checkers=['eslint']
```
