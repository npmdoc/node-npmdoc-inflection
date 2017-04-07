# api documentation for  [inflection (v1.12.0)](https://github.com/dreamerslab/node.inflection#readme)  [![npm package](https://img.shields.io/npm/v/npmdoc-inflection.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-inflection) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-inflection.svg)](https://travis-ci.org/npmdoc/node-npmdoc-inflection)
#### A port of inflection-js to node.js module

[![NPM](https://nodei.co/npm/inflection.png?downloads=true)](https://www.npmjs.com/package/inflection)

[![apidoc](https://npmdoc.github.io/node-npmdoc-inflection/build/screenCapture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-inflection_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-inflection/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-inflection/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-inflection/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "dreamerslab",
        "email": "ben@dreamerslab.com"
    },
    "bugs": {
        "url": "https://github.com/dreamerslab/node.inflection/issues"
    },
    "contributors": [
        {
            "name": "Ryan Schuft",
            "email": "ryan.schuft@gmail.com"
        },
        {
            "name": "Ben Lin",
            "email": "ben@dreamerslab.com"
        },
        {
            "name": "Lance Pollard",
            "email": "lancejpollard@gmail.com"
        },
        {
            "name": "Dane O'Connor",
            "email": "dane.oconnor@gmail.com"
        },
        {
            "name": "David Miró",
            "email": "lite.3engine@gmail.com"
        },
        {
            "name": "brandondewitt"
        },
        {
            "name": "luk3thomas"
        },
        {
            "name": "Marcel Klehr"
        },
        {
            "name": "Raymond Feng"
        },
        {
            "name": "Kane Cohen",
            "email": "kanecohen@gmail.com"
        },
        {
            "name": "Gianni Chiappetta",
            "email": "gianni@runlevel6.org"
        },
        {
            "name": "Eric Brody"
        },
        {
            "name": "overlookmotel"
        },
        {
            "name": "Patrick Mowrer"
        },
        {
            "name": "Greger Olsson"
        },
        {
            "name": "Jason Crawford",
            "email": "jason@jasoncrawford.org"
        },
        {
            "name": "Ray Myers",
            "email": "ray.myers@gmail.com"
        },
        {
            "name": "Dillon Shook",
            "email": "dshook@alumni.nmt.edu"
        }
    ],
    "dependencies": {},
    "description": "A port of inflection-js to node.js module",
    "devDependencies": {
        "mocha": "3.2.0",
        "should": "11.2.0"
    },
    "directories": {},
    "dist": {
        "shasum": "a200935656d6f5f6bc4dc7502e1aecb703228416",
        "tarball": "https://registry.npmjs.org/inflection/-/inflection-1.12.0.tgz"
    },
    "engines": [
        "node >= 0.4.0"
    ],
    "gitHead": "6cfc616ab8fbb04fc52ed428926cc021d87d6c14",
    "homepage": "https://github.com/dreamerslab/node.inflection#readme",
    "keywords": [
        "inflection",
        "inflections",
        "inflection-js",
        "pluralize",
        "singularize",
        "camelize",
        "underscore",
        "humanize",
        "capitalize",
        "dasherize",
        "titleize",
        "demodulize",
        "tableize",
        "classify",
        "foreign_key",
        "ordinalize"
    ],
    "license": "MIT",
    "main": "./lib/inflection.js",
    "maintainers": [
        {
            "name": "dreamerslab",
            "email": "ben@dreamerslab.com"
        }
    ],
    "name": "inflection",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/dreamerslab/node.inflection.git"
    },
    "scripts": {
        "test": "mocha -R spec"
    },
    "version": "1.12.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module inflection](#apidoc.module.inflection)
1.  [function <span class="apidocSignatureSpan">inflection.</span>_apply_rules ( str, rules, skip, override )](#apidoc.element.inflection._apply_rules)
1.  [function <span class="apidocSignatureSpan">inflection.</span>camelize ( str, low_first_letter )](#apidoc.element.inflection.camelize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>capitalize ( str )](#apidoc.element.inflection.capitalize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>classify ( str )](#apidoc.element.inflection.classify)
1.  [function <span class="apidocSignatureSpan">inflection.</span>dasherize ( str )](#apidoc.element.inflection.dasherize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>demodulize ( str )](#apidoc.element.inflection.demodulize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>foreign_key ( str, drop_id_ubar )](#apidoc.element.inflection.foreign_key)
1.  [function <span class="apidocSignatureSpan">inflection.</span>humanize ( str, low_first_letter )](#apidoc.element.inflection.humanize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>indexOf ( arr, item, from_index, compare_func )](#apidoc.element.inflection.indexOf)
1.  [function <span class="apidocSignatureSpan">inflection.</span>inflect ( str, count, singular, plural )](#apidoc.element.inflection.inflect)
1.  [function <span class="apidocSignatureSpan">inflection.</span>ordinalize ( str )](#apidoc.element.inflection.ordinalize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>pluralize ( str, plural )](#apidoc.element.inflection.pluralize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>singularize ( str, singular )](#apidoc.element.inflection.singularize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>tableize ( str )](#apidoc.element.inflection.tableize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>titleize ( str )](#apidoc.element.inflection.titleize)
1.  [function <span class="apidocSignatureSpan">inflection.</span>transform ( str, arr )](#apidoc.element.inflection.transform)
1.  [function <span class="apidocSignatureSpan">inflection.</span>underscore ( str, all_upper_case )](#apidoc.element.inflection.underscore)
1.  string <span class="apidocSignatureSpan">inflection.</span>version



# <a name="apidoc.module.inflection"></a>[module inflection](#apidoc.module.inflection)

#### <a name="apidoc.element.inflection._apply_rules"></a>[function <span class="apidocSignatureSpan">inflection.</span>_apply_rules ( str, rules, skip, override )](#apidoc.element.inflection._apply_rules)
- description and source-code
```javascript
_apply_rules = function ( str, rules, skip, override ){
  if( override ){
    str = override;
  }else{
    var ignore = ( inflector.indexOf( skip, str.toLowerCase()) > -1 );

    if( !ignore ){
      var i = 0;
      var j = rules.length;

      for( ; i < j; i++ ){
        if( str.match( rules[ i ][ 0 ])){
          if( rules[ i ][ 1 ] !== undefined ){
            str = str.replace( rules[ i ][ 0 ], rules[ i ][ 1 ]);
          }
          break;
        }
      }
    }
  }

  return str;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.inflection.camelize"></a>[function <span class="apidocSignatureSpan">inflection.</span>camelize ( str, low_first_letter )](#apidoc.element.inflection.camelize)
- description and source-code
```javascript
camelize = function ( str, low_first_letter ){
  var str_path = str.split( '/' );
  var i        = 0;
  var j        = str_path.length;
  var str_arr, init_x, k, l, first;

  for( ; i < j; i++ ){
    str_arr = str_path[ i ].split( '_' );
    k       = 0;
    l       = str_arr.length;

    for( ; k < l; k++ ){
      if( k !== 0 ){
        str_arr[ k ] = str_arr[ k ].toLowerCase();
      }

      first = str_arr[ k ].charAt( 0 );
      first = low_first_letter && i === 0 && k === 0
        ? first.toLowerCase() : first.toUpperCase();
      str_arr[ k ] = first + str_arr[ k ].substring( 1 );
    }

    str_path[ i ] = str_arr.join( '' );
  }

  return str_path.join( '::' );
}
```
- example usage
```shell
...

## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
...
```

#### <a name="apidoc.element.inflection.capitalize"></a>[function <span class="apidocSignatureSpan">inflection.</span>capitalize ( str )](#apidoc.element.inflection.capitalize)
- description and source-code
```javascript
capitalize = function ( str ){
  str = str.toLowerCase();

  return str.substring( 0, 1 ).toUpperCase() + str.substring( 1 );
}
```
- example usage
```shell
...
- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
...
```

#### <a name="apidoc.element.inflection.classify"></a>[function <span class="apidocSignatureSpan">inflection.</span>classify ( str )](#apidoc.element.inflection.classify)
- description and source-code
```javascript
classify = function ( str ){
  str = inflector.camelize( str );
  str = inflector.singularize( str );

  return str;
}
```
- example usage
```shell
...
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );



## Usage
...
```

#### <a name="apidoc.element.inflection.dasherize"></a>[function <span class="apidocSignatureSpan">inflection.</span>dasherize ( str )](#apidoc.element.inflection.dasherize)
- description and source-code
```javascript
dasherize = function ( str ){
  return str.replace( space_or_underbar, '-' );
}
```
- example usage
```shell
...
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );
...
```

#### <a name="apidoc.element.inflection.demodulize"></a>[function <span class="apidocSignatureSpan">inflection.</span>demodulize ( str )](#apidoc.element.inflection.demodulize)
- description and source-code
```javascript
demodulize = function ( str ){
  var str_arr = str.split( '::' );

  return str_arr[ str_arr.length - 1 ];
}
```
- example usage
```shell
...
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );
...
```

#### <a name="apidoc.element.inflection.foreign_key"></a>[function <span class="apidocSignatureSpan">inflection.</span>foreign_key ( str, drop_id_ubar )](#apidoc.element.inflection.foreign_key)
- description and source-code
```javascript
foreign_key = function ( str, drop_id_ubar ){
  str = inflector.demodulize( str );
  str = inflector.underscore( str ) + (( drop_id_ubar ) ? ( '' ) : ( '_' )) + 'id';

  return str;
}
```
- example usage
```shell
...
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );



## Usage
...
```

#### <a name="apidoc.element.inflection.humanize"></a>[function <span class="apidocSignatureSpan">inflection.</span>humanize ( str, low_first_letter )](#apidoc.element.inflection.humanize)
- description and source-code
```javascript
humanize = function ( str, low_first_letter ){
  str = str.toLowerCase();
  str = str.replace( id_suffix, '' );
  str = str.replace( underbar, ' ' );

  if( !low_first_letter ){
    str = inflector.capitalize( str );
  }

  return str;
}
```
- example usage
```shell
...

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
...
```

#### <a name="apidoc.element.inflection.indexOf"></a>[function <span class="apidocSignatureSpan">inflection.</span>indexOf ( arr, item, from_index, compare_func )](#apidoc.element.inflection.indexOf)
- description and source-code
```javascript
indexOf = function ( arr, item, from_index, compare_func ){
  if( !from_index ){
    from_index = -1;
  }

  var index = -1;
  var i     = from_index;
  var j     = arr.length;

  for( ; i < j; i++ ){
    if( arr[ i ]  === item || compare_func && compare_func( arr[ i ], item )){
      index = i;
      break;
    }
  }

  return index;
}
```
- example usage
```shell
...

	npm install inflection



## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
...
```

#### <a name="apidoc.element.inflection.inflect"></a>[function <span class="apidocSignatureSpan">inflection.</span>inflect ( str, count, singular, plural )](#apidoc.element.inflection.inflect)
- description and source-code
```javascript
inflect = function ( str, count, singular, plural ){
  count = parseInt( count, 10 );

  if( isNaN( count )) return str;

  if( count === 0 || count > 1 ){
    return inflector._apply_rules( str, plural_rules, uncountable_words, plural );
  }else{
    return inflector._apply_rules( str, singular_rules, uncountable_words, singular );
  }
}
```
- example usage
```shell
...


## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
...
```

#### <a name="apidoc.element.inflection.ordinalize"></a>[function <span class="apidocSignatureSpan">inflection.</span>ordinalize ( str )](#apidoc.element.inflection.ordinalize)
- description and source-code
```javascript
ordinalize = function ( str ){
  var str_arr = str.split( ' ' );
  var i       = 0;
  var j       = str_arr.length;

  for( ; i < j; i++ ){
    var k = parseInt( str_arr[ i ], 10 );

    if( !isNaN( k )){
      var ltd = str_arr[ i ].substring( str_arr[ i ].length - 2 );
      var ld  = str_arr[ i ].substring( str_arr[ i ].length - 1 );
      var suf = 'th';

      if( ltd != '11' && ltd != '12' && ltd != '13' ){
        if( ld === '1' ){
          suf = 'st';
        }else if( ld === '2' ){
          suf = 'nd';
        }else if( ld === '3' ){
          suf = 'rd';
        }
      }

      str_arr[ i ] += suf;
    }
  }

  return str_arr.join( ' ' );
}
```
- example usage
```shell
...
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );



## Usage

> Require the module before using
...
```

#### <a name="apidoc.element.inflection.pluralize"></a>[function <span class="apidocSignatureSpan">inflection.</span>pluralize ( str, plural )](#apidoc.element.inflection.pluralize)
- description and source-code
```javascript
pluralize = function ( str, plural ){
  return inflector._apply_rules( str, plural_rules, uncountable_words, plural );
}
```
- example usage
```shell
...
	npm install inflection



## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
...
```

#### <a name="apidoc.element.inflection.singularize"></a>[function <span class="apidocSignatureSpan">inflection.</span>singularize ( str, singular )](#apidoc.element.inflection.singularize)
- description and source-code
```javascript
singularize = function ( str, singular ){
  return inflector._apply_rules( str, singular_rules, uncountable_words, singular );
}
```
- example usage
```shell
...



## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
...
```

#### <a name="apidoc.element.inflection.tableize"></a>[function <span class="apidocSignatureSpan">inflection.</span>tableize ( str )](#apidoc.element.inflection.tableize)
- description and source-code
```javascript
tableize = function ( str ){
  str = inflector.underscore( str );
  str = inflector.pluralize( str );

  return str;
}
```
- example usage
```shell
...
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );
...
```

#### <a name="apidoc.element.inflection.titleize"></a>[function <span class="apidocSignatureSpan">inflection.</span>titleize ( str )](#apidoc.element.inflection.titleize)
- description and source-code
```javascript
titleize = function ( str ){
  str         = str.toLowerCase().replace( underbar, ' ' );
  var str_arr = str.split( ' ' );
  var i       = 0;
  var j       = str_arr.length;
  var d, k, l;

  for( ; i < j; i++ ){
    d = str_arr[ i ].split( '-' );
    k = 0;
    l = d.length;

    for( ; k < l; k++){
      if( inflector.indexOf( non_titlecased_words, d[ k ].toLowerCase()) < 0 ){
        d[ k ] = inflector.capitalize( d[ k ]);
      }
    }

    str_arr[ i ] = d.join( '-' );
  }

  str = str_arr.join( ' ' );
  str = str.substring( 0, 1 ).toUpperCase() + str.substring( 1 );

  return str;
}
```
- example usage
```shell
...
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );
...
```

#### <a name="apidoc.element.inflection.transform"></a>[function <span class="apidocSignatureSpan">inflection.</span>transform ( str, arr )](#apidoc.element.inflection.transform)
- description and source-code
```javascript
transform = function ( str, arr ){
  var i = 0;
  var j = arr.length;

  for( ;i < j; i++ ){
    var method = arr[ i ];

    if( inflector.hasOwnProperty( method )){
      str = inflector[ method ]( str );
    }
  }

  return str;
}
```
- example usage
```shell
...
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
- inflection.foreign_key( str, drop_id_ubar );
- inflection.ordinalize( str );
- inflection.transform( str, arr );



## Usage

> Require the module before using
...
```

#### <a name="apidoc.element.inflection.underscore"></a>[function <span class="apidocSignatureSpan">inflection.</span>underscore ( str, all_upper_case )](#apidoc.element.inflection.underscore)
- description and source-code
```javascript
underscore = function ( str, all_upper_case ){
  if( all_upper_case && str === str.toUpperCase()) return str;

  var str_path = str.split( '::' );
  var i        = 0;
  var j        = str_path.length;

  for( ; i < j; i++ ){
    str_path[ i ] = str_path[ i ].replace( uppercase, '_$1' );
    str_path[ i ] = str_path[ i ].replace( underbar_prefix, '' );
  }

  return str_path.join( '/' ).toLowerCase();
}
```
- example usage
```shell
...
## API

- inflection.indexOf( arr, item, from_index, compare_func );
- inflection.pluralize( str, plural );
- inflection.singularize( str, singular );
- inflection.inflect( str, count, singular, plural );
- inflection.camelize( str, low_first_letter );
- inflection.underscore( str, all_upper_case );
- inflection.humanize( str, low_first_letter );
- inflection.capitalize( str );
- inflection.dasherize( str );
- inflection.titleize( str );
- inflection.demodulize( str );
- inflection.tableize( str );
- inflection.classify( str );
...
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
