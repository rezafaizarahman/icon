# mltrgt-icon [mltrgt.github.io/icon](https://mltrgt.github.io/icon/)

Iconfont untuk [mailtarget.co](http://mailtarget.co)

Dibuat menggunakan [gulp-sketch](https://github.com/cognitom/gulp-sketch), [gulp-iconfont](https://github.com/nfroidure/gulp-iconfont) dan template dari [symbols-for-sketch](https://github.com/cognitom/symbols-for-sketch).


## Getting Started

### How to use

#### Embed Using CSS
``` html
<link href="https://mltrgt.github.io/icon/css/mltrgt-icon.css" rel="stylesheet">
```
or
``` css
@import url(https://mltrgt.github.io/icon/css/mltrgt-icon.css);
```


#### Example
``` html
<span class="mt-emoji"></span>
```

### Build icon
Install dependencies:
``` bash
$ npm install
```

Generate:
``` bash
$ npm run symbols
```

Live reload:
``` bash
$ npm start
```

Menambahkan icon baru:
- Buka mltrgt-icon-template.sketch
- Buat artboard baru (512x512 px)
- Tambahkan icon ke dalam artboard tersebut
- Save
- Generate
