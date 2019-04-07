# fis-optimizer-way2enjoy

A optimizer for fis to compress JPG,PNG, GIF, PDF, MP3, MP4 by using way2enjoy.
## use
```node
npm install --save fis-optimizer-way2enjoy
```
Application for key
https://way2enjoy.com/developers

## settings
```javascript
//file : path/to/project/fis-conf.js
fis.match('/img/(*.{jpg,png})', {
    optimizer: fis.plugin('way2enjoy', {
        to: '../output/img',
        key: 'xxxxxxxxxxxxxxxxxxxxxx'
    })
});
```
