# Neumorphism_Checkbox

# Installation :

1. Copy the neumorph_checkbox folder in your repo.
2. Add neumorphism as a dependency in your package.json file.

```json
{
  "dependencies": {
    "neumorphism": "file:../neumorph_checkbox"
  }
}
```

# Note :

Add this css snippet when passing input or button through slot .

```css
button, input{
    width: 100%;
    height: 100%;
    background-color:transparent;
    text-color: black;
}
```

# Checkbox

<img src="sample_images/checkbox.png" width="" height="">

Import:
```html
<element name='neucheckbox' src='../../../../../../node_modules/neumorphism/checkbox/checkbox.hml'></element>
```

Usage:
```html
<neucheckbox color="" width="50px" height="50px" border="50px" checked="true" @check-event="checkboxClick"></neucheckbox>
```

# Radio

<img src="sample_images/radio.png" width="" height="">

Import:
```html
<element name='neuradio' src='../../../../../../node_modules/neumorphism/radio/radio.hml'></element>
```

Usage:
```html
<neuradio width="50px" color="" height="50px" border="50px" checked="" @check-event="radioClick"></neuradio>
```

# Switcher

<img src="sample_images/switcher.png" width="" height="">

Import:
```html
<element name='neuswitcher' src='../../../../../../node_modules/neumorphism/switcher/switcher.hml'></element>
```

Usage:
```html
<neuswitcher width="60px" color="" height="30px" border="50px" toggle="off" @toggle-event="toggleClick"></neuswitcher>
```
