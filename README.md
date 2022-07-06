# stencil-lib

POC project for angular component library using stencil 

## How to use 
1. Invoke this in the consumer app 
2. Add 'CUSTOM_ELEMENTS_SCHEMA' in app module 
3. Import componment in app module and call defineCustomElements function to register the web component in browser DOM
```

import { defineCustomElements } from 'jimmy-angular-lib/loader';
defineCustomElements(window);

```
4. In any of the html file, use this component, example
```                
<my-component></my-component>
```

## Publish locally 
To be added ... 