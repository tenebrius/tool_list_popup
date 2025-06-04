

## Usage

1. Add className "tool-list-container" to your logo div (the icon only). This script will replace the content with the proper icon and popup

Example:
```
    <div class="tool-list-container" style="position:absolute; width:74px; height:74px">
    
    </div>
```

2. Add this to your HTML



```
    <script src="https://align.marshub.com/assets/tools-list/popup.js"></script>
    <link rel="stylesheet" href="https://align.marshub.com/assets/tools-list/popup.css">
```


3. To change language, call the 'window.toolListPopup.setLocale' function
e. 
```
window.toolListPopup.setLocale('en')
or 
window.toolListPopup.setLocale('zh')

```
It will remember the last language set via localStorage key 'toolListPopupLocale'