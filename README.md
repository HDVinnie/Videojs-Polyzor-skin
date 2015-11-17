## Start-Kit
> Fast start (launch control)

### Template include
- [Normalize.css 3.0.2](http://necolas.github.io/normalize.css/)
- [jQuery 1.11.3](http://jquery.com/download/)

### Use project builder (with Gulp.js)
1. download devDependencies 
```sh 
$ npm install 
```
2. Create your webApp in real time with browserSync
```sh 
$ gulp server
```
3. Prepare your webApp for production 
```sh 
$ gulp dist
```
4. Test production ver. local 
```sh 
$ gulp server:dist
```

#### Notice:
##### Foundation
>> @media break points SASS
```
>>> .class {
        text-align: center;
        padding: 0;
        @media #{$large-up} {
            padding: 0 100px 0 100px;
        }
    }
```
##### IDE
>> Set-up jade watcher in WebStorm:
``` sh
$FileName$ -P --out $ProjectFileDir$/app
```
