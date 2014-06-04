# Brunch app

## To see them problem
* Clone this repo
* Ensure you're using brunch v. 1.7.14 (brunch --version)
* Run ```bower install```
* Run ```brunch b```
Observe, this error is encountered:
```
/usr/local/lib/node_modules/brunch/node_modules/read-components/index.js:108
    pkg[property].forEach(function(item) {
                  ^
TypeError: Object #<Object> has no method 'forEach'
  at /usr/local/lib/node_modules/brunch/node_modules/read-components/index.js:108:19
  at Array.forEach (native)
  at exports.getPackageFiles (/usr/local/lib/node_modules/brunch/node_modules/read-components/index.js:107:13)
  at /usr/local/lib/node_modules/brunch/node_modules/read-components/index.js:138:19
  at /usr/local/lib/node_modules/brunch/node_modules/read-components/index.js:87:7
  at fs.js:266:14
  at Object.oncomplete (fs.js:107:15)
```
