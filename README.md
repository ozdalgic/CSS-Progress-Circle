## CSS Progress Circle

Visit the [Web Page](https://ozdalgic.github.io/CSS-Progress-Circle/)
    
#### Animation or Fixed, Dark or Light, Flexible Customization
![thumbnail](https://raw.githubusercontent.com/ozdalgic/CSS-Progress-Circle/master/example/assets/img/thumbnail.png)

## Use
##### Live Demo
- [Light Theme & No Animation](https://codepen.io/ozdalgic/pen/abOoBoV)
- [Dark Theme & Animation](https://codepen.io/ozdalgic/pen/ZEGzpPB)
- [Light Theme & Animation](https://codepen.io/ozdalgic/pen/ZEGzpMO)

##### CSS
    <link href="localpath/circle-progress.css" rel="stylesheet">

##### SCSS
    @import "localpath/circle-progress.scss";

##### Font Optional
    <link href="https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap&subset=latin-ext" rel="stylesheet">

##### HTML
```html
<div data-value="30"><div data-progress-type="POINT"></div></div>
```

###### Default
```html
<div data-value="0" style="
        --circle-size:100px;
        --inline-circle-size:80%;
        --border-width:5px;
        --border-color:#eee;
        --font: 'Poppins', sans-serif;
        --bg-color: #fff;
"><div data-progress-type="POINT"></div>
</div> 
```

### Options

Option | Value
--- | --- 
**data-value** | `0 to 100 number:value`
**data-progress-type** | `string`
**--circle-size** | `number:value:pixel`
**--inline-circle-size** | `number:value:percent` 
**--border-width** | `number:value:pixel`
**--border-color** | `color:hex`
**--font** | `font-family:optional`
**--bg-color** | `color:hex`
