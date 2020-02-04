## CSS Circle Progress

Visit the [Web Page](https://ozdalgic.github.io/CSS-Circle-Progress/)
    
#### Animation or Fixed, Dark or Light, Flexible Customization
![thumbnail](https://raw.githubusercontent.com/ozdalgic/CSS-Circle-Progress/master/example/assets/img/thumbnail.png)

## Use
##### CSS
    <link href="assets/css/circle-progress.css" rel="stylesheet">

##### Font Optional
    <link href="https://fonts.googleapis.com/css?family=Poppins:400,700&display=swap&subset=latin-ext" rel="stylesheet">

##### HTML
```html
<div data-value="0" style="
        --circle-size:50px;
        --inline-circle-size:80%;
        --inline-background: red;
        --border-width:3px;
        --border-color:#eee;
        --font: 'Poppins', sans-serif;
        --bg-color: #fefefe;
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
