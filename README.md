#fis-postprocessor-cssgrace

##INSTALL

```
npm install -g fis-postprocessor-cssgrace
```

##USE:

**fis3:**

```javascript
fis.match('*.css', {
    postprocessor: fis.plugin('cssgrace')
});
```

**fis**

```javascript
fis.config.set('modules.postprocessor.css', 'cssgrace');
```