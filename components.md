# `Foo` Component

### Importing the component module `FooComponent`.
> Components are found in the `./src/Components` folder.

```js
import FooComponent from './Components/FooComponent';
```

Using the `component`
```html
<FooComponent
  prop1=""
  prop2=""
  prop3=""
  />

  <FooComponent
    prop1=""
    prop2=""
    prop3=""
  >
  ...
  </FooComponent>
```


### Properties
* `store` = `Mobx Store`
* `direction` = `'down'` or `'up'`
* `height` = number from `0` to `100`
* `open` = `true` or `false`
* `onOpen` = callback `function`
* `onClose` = callback `function`

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/foo_component.png "Logo Title Text 1" )





# `SlideSidebar` Component

### Importing the component module `SlideSidebar`.
> Components are found in the `./src/Components` folder.

```js
// Mobx Store, to store the state of  SlideSidebar
import LayoutStore from './store/LayoutStore';

import SlideSidebar from './Components/SlideSidebar';
```

Initiate the state
```js

constructor(){
    super();
    this.state= {
      isSideMenuOpen: false
    };
  }

```


Using the Component
```html
<SlideSidebar
    store={LayoutStore}
    direction="left"
    open={this.state.isSideMenuOpen}
    onOpen={()=>this.setState({isSideMenuOpen:true})}
    onClose={()=>this.setState({isSideMenuOpen:false})}
  >
    ...
</SlideSidebar>
```


### Properties
* `store` = `Mobx Store`
* `direction` = `'left'` or `'right'`
* `open` = `true` or `false`
* `onOpen` = callback `function`
* `onClose` = callback `function`

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/SlideSidebar_component.png "Logo Title Text 1" )














# `SlideOverlay` Component

### Importing the component module `SlideOverlay`.
> Components are found in the `./src/Components` folder.

```js
// Mobx Store, to store the state of  SlideSidebar
import LayoutStore from './store/LayoutStore';

import SlideOverlay from './Components/SlideOverlay';
```

Initiate the state
```js

constructor(){
    super();
    this.state= {
      openSearchOverlay: false
    };
  }

```


Using the Component
```html
<SlideOverlay
    store={LayoutStore}
    direction="down"
    height={100}
    open={this.state.openSearchOverlay}
    onClose={()=>this.setState({openSearchOverlay:false})}
    onOpen={()=>this.setState({openSearchOverlay:true})}
  >
            .....

</SlideOverlay>
```

### Properties
* `store` = `Mobx Store`
* `direction` = `'down'` or `'up'`
* `height` = number from `0` to `100`
* `open` = `true` or `false`
* `onOpen` = callback `function`
* `onClose` = callback `function`

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/SlideOverlay_component.png "Logo Title Text 1" )








# `Portlet` Component

### Importing the component module `Portlet`.
> Components are found in the `./src/Components` folder.

```js
import Portlet from './Components/Portlet';
```


Using the Component
```html
<Portlet
  title = 'title',
  height=250,
  isControls,
  isClose=true,
  isCollapse=true,
  isExpand=true,
  isHeader=true,
  style={},
  className ='custom class names'
>
            .....

</Portlet>
```

### Properties
* `title` = `string`
* `height` = `number`
* `isControls` = `true` or `false`
* `isClose` = `true` or `false`
* `isCollapse` = `true` or `false`
* `isExpand` = `true` or `false`
* `isHeader` = `true` or `false`
* `style` = styles object `{{height:100, width:30}}`
* `className` = string `class1 class2`

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/Portlet_component.png "Logo Title Text 1" )
