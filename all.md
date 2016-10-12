# Installation



## Requirements

To get started make sure you have node.js installed

> Install Node.js
> https://nodejs.org/en/download/

Unzip the package, update NPM and install the app dependencies

```
➔ cd raspberry-react-admin
➔ npm install
```
At this point you can run the project in debug mode :
```
➔ npm start
```
Or build a production SPA :
```
➔ npm run build
```


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!



## Folder Structure

After creation, your project should look like this:

```
.
├── AppStyles
│   └── tabs
│       └── index
├── Apps
│   ├── CalendarApp
│   ├── InboxApp
│   ├── MapsApp
│   │   └── assets
│   ├── MessagesApp
│   ├── NumbersApp
│   │   └── assets
│   └── ProjectsApp
├── Components
│   ├── Aside
│   ├── Charts
│   ├── Comments
│   ├── DashboardStat
│   ├── Feeds
│   ├── Gallery
│   ├── Navbar
│   ├── PageBar
│   ├── Portlet
│   ├── QuickActions
│   └── SecondaryAside
├── Pages
│   ├── BaloonPage
│   ├── BlogPage
│   ├── ColorPalettePage
│   ├── ColorPickersPage
│   ├── DashboardPage
│   ├── DatePickerPage
│   ├── DialogPage
│   ├── DocsPage
│   ├── DraftEditorPage
│   ├── FormsPage
│   ├── FullCalendarPage
│   ├── GalleryPage
│   ├── GeneralUIPage
│   ├── HandsontablePage
│   ├── IconsPage
│   ├── InvoicePage
│   ├── LandingPage
│   │   └── contents
│   ├── LayoutsPage
│   │   ├── Layouts
│   │   └── assets
│   ├── ListsPage
│   ├── LoginPage
│   ├── NavigationPage
│   ├── OverlayPage
│   ├── Page404
│   ├── PortletsPage
│   ├── RegisterPage
│   ├── ResponsivePage
│   ├── SidebarsPage
│   ├── SlickCarouselPage
│   ├── TabsPage
│   ├── TemplatePage
│   ├── TimelinePage
│   └── TypographyPage
├── Sidebar
├── Themes
│   ├── Dark
│   └── Light
├── UI
├── data
├── store
└── widgets
    ├── ActionCardWidget
    │   └── images
    ├── ActivitiesListWidget
    ├── ChatWidget
    ├── ContactsListWidget
    ├── LineChartWidget
    ├── MessagesWidget
    ├── ProjectsListWidget
    ├── SearchWidget
    ├── SocialProfileWidget
    ├── StatisticsPanel
    ├── StatisticsPanelWidget
    └── TasksListWidget

```




###  Styling with LESS or CSS

The application style is built on bootstrap and is developed in LESS to provide bulk wholesale changes. The LESS files can be found in each component, page or widget folder

We use LiveReload to compile and watch the LESS files.

LiveReload monitors changes in the file system. As soon as you save a file
`Download` [livereload]( http://livereload.com/) to s






# Inbox App

### Importing the app module `InboxApp`.
> Apps are found in the `./src/Apps` folder.

```js
import InboxApp from './Apps/InboxApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="inbox/" component={InboxApp}/>
    </Route>
</Route>
```


![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/inbox_app.png "Logo Title Text 1" )


# Calendar App

### Importing the app module `CalendarApp`.
> Apps are found in the `./src/Apps` folder.

```js
import CalendarApp from './Apps/CalendarApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="calendar/" component={CalendarApp}/>
    </Route>
</Route>

```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/calendar_app.png "Logo Title Text 1" )


# Numbers  App


### Importing the app module `NumbersApp`.
> Apps are found in the `./src/Apps` folder.

```js
import NumbersApp from './Apps/NumbersApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="numbers/" component={NumbersApp}/>
    </Route>
</Route>

```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/numbers_app.png "Logo Title Text 1" )



# Maps App


### Importing the app module `MapsApp`.
> Apps are found in the `./src/Apps` folder.

```js
import MapsApp from './Apps/MapsApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="maps/" component={MapsApp}/>
    </Route>
</Route>

```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/maps_app.png "Logo Title Text 1" )



# Projects App


### Importing the app module `ProjectsApp`.
> Apps are found in the `./src/Apps` folder.

```js
import ProjectsApp from './Apps/ProjectsApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="projects/" component={ProjectsApp}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/projects_app.png "Logo Title Text 1" )



# Messages App


### Importing the app module `MessagesApp`.
> Apps are found in the `./src/Apps` folder.

```js
import MessagesApp from './Apps/MessagesApp';
```

Configuring the route
```html
<Route path="/" component={UI.Layout}>
    <Route path="/apps/" component={UI.ResponsiveLayout} >
      <Route path="messages/" component={MessagesApp}/>
    </Route>
</Route>

```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/messages_app.png "Logo Title Text 1" )




# Dashboard Page

## Importing the page module `DashboardPage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import DashboardPage from './Pages/DashboardPage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/pages/" component={UI.ResponsiveLayout} >
      <Route path="dashboard/" component={DashboardPage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/dashboard_page.png "Logo Title Text 1")





# Blog Page

## Importing the page module `BlogPage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import BlogPage from './Pages/BlogPage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/pages/" component={UI.ResponsiveLayout} >
      <Route path="blog/" component={BlogPage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/blog_page.png "Logo Title Text 1")






# Timeline Page

## Importing the page module `TimelinePage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import TimelinePage from './Pages/TimelinePage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/pages/" component={UI.ResponsiveLayout} >
      <Route path="timeline/" component={TimelinePage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/timeline_page.png "Logo Title Text 1")



# Invoice Page

## Importing the page module `InvoicePage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import InvoicePage from './Pages/InvoicePage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/pages/" component={UI.ResponsiveLayout} >
      <Route path="invoice/" component={InvoicePage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/invoice_page.png "Logo Title Text 1")





# Login Page

## Importing the page module `LoginPage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import LoginPage from './Pages/LoginPage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/users/" >
      <Route path="login/" component={LoginPage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/login_page.png "Logo Title Text 1")



# Register Page

## Importing the page module `RegisterPage`.

> Pages are found in the `./src/Pages` folder.

```javascript
import RegisterPage from './Pages/RegisterPage';
```

Configuring the route

```html
<Route path="/" component={UI.Layout}>
    <Route path="/users/" >
      <Route path="register/" component={RegisterPage}/>
    </Route>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/register_page.png "Logo Title Text 1")





# 404 Page

## Importing the page module `Page404`.

> Pages are found in the `./src/Pages` folder.

```javascript
import Page404 from './Pages/Page404';
```

Configuring the route

```html
<Route path="*">
  <IndexRedirect to="/error/404/"/>
</Route>
```

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/404_page.png "Logo Title Text 1")






---



# Layouts

# Bootstrap Layout

### Importing the component modules.

```js
import { Container, Row, Col } from 'reactstrap';
```

Using the `components`
```html
  <Container>
    <Row>
      <Col>col-xs-12</Col>
    </Row>
    <Row>
      <Col xs="6">col-xs-6</Col>
      <Col xs="6">col-xs-6</Col>
    </Row>
    <Row>
      <Col xs="6" sm="4">col-xs-6 col-sm-4</Col>
      <Col xs="6" sm="4">col-xs-6 col-sm-4</Col>
      <Col sm="4">col-xs-12 col-sm-4</Col>
    </Row>
    <Row>
      <Col sm={{ size: 6, push: 2, pull: 2, offset: 1 }}>.col-xs-12 .col-sm-6 .col-sm-push-2 .col-sm-pull-2 .col-sm-offset-2</Col>
    </Row>
    <Row>
      <Col sm="12" md={{ size: 8, offset: 2 }}>.col-xs-12 .col-sm-12 .col-md-6 .col-md-offset-3</Col>
    </Row>
  </Container>


```

## Properties
* xs: columnProps
* sm: columnProps
* md: columnProps
* lg: columnProps
* xl: columnProps

![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/bootstrap_layout.png "Logo Title Text 1" )














# Tabular Layout

### Importing the component modules.

```js
import { T, R, D } from '../../../UI/TableLayout';
```
Using the `components`

```html
<T className="wrapper layout-1">
  <R>
    <D className=" wrapper-xs " style={{width:90}}>
      ...
    </D>
    <D className=" wrapper-xs ">
      ...
    </D>
    <D className=" wrapper-xs " style={{width:'30%'}}>
      .....
    </D>
  </R>
</T>


```

## Properties
* className
* style


![alt text](https://raw.githubusercontent.com/abusafa/react-admin-template-doc/master/tabular_layout.png "Logo Title Text 1" )



 -----


 # Credits


 name | version | repo
 --- | ---  | ---
 react | `15.3.2` | `git+https://github.com/facebook/react.git`
 bootstrap | `4.0.0-alpha.4` | `git+https://github.com/twbs/bootstrap.git`
 moment | `2.15.1` | `git+https://github.com/moment/moment.git`
 lodash | `1.4.0` | `git+https://github.com/lodash/lodash.git`
 babeljs | | `https://github.com/babel/babel.git`
 webpack | | `https://github.com/webpack/webpack.git`
 boron | `0.2.3` | `git+https://github.com/yuanyan/boron.git`
 chart.js | `2.3.0` | `git+https://github.com/chartjs/Chart.js.git`
 classnames | `2.2.5` | `git+https://github.com/JedWatson/classnames.git`
 color | `0.11.3` | `git+https://github.com/qix-/color.git`
 draft-js | `0.9.1` | `git+https://github.com/facebook/draft-js.git`
 faker | `3.1.0` | `https://github.com/practicalmeteor/meteor-faker.git`
 halogen | `0.2.0` | `git+https://github.com/yuanyan/halogen.git`
 handsontable | `0.28.0` | `git+https://github.com/handsontable/handsontable.git`
 material-colors | `1.1.1` | `git+https://github.com/shuhei/material-colors.git`
 mobx | `2.5.2` | `git+https://github.com/mobxjs/mobx.git`
 rc-tabs | `7.0.10` | `git+ssh://git@github.com/react-component/tabs.git`
 react-big-calendar | `0.10.3` | `git+https://github.com/intljusticemission/react-big-calendar.git`
 react-chartjs-2 | `1.2.5` | `git+https://github.com/gor181/react-chartjs-2.git`
 react-color | `2.3.2` | `git+https://github.com/casesandberg/react-color.git`
 react-custom-scrollbars | `4.0.0` | `git+https://github.com/malte-wessel/react-custom-scrollbars.git`
 react-google-maps | `4.11.0` | `git+https://github.com/tomchentw/react-google-maps.git`
 react-grid-layout | `0.13.6` | `git+ssh://git@github.com/STRML/react-grid-layout.git`
 react-helmet | `3.1.0` | `git+https://github.com/nfl/react-helmet.git`
 react-images | `0.5.1` | `git+https://github.com/jossmac/react-images.git`
 react-jsonschema-form | `0.40.0` | `git+https://github.com/mozilla-services/react-jsonschema-form.git`
 react-markdown | `2.4.2` | `git+ssh://git@github.com/rexxars/react-markdown.git`
 react-motion | `0.4.4` | `git+https://github.com/chenglou/react-motion.git`
 react-responsive | `1.1.5` | `git://github.com/wearefractal/react-responsive.git`
 react-router | `2.8.1` | `git+https://github.com/reactjs/react-router.git`
 react-select | `1.0.0-rc.2` | `git+https://github.com/JedWatson/react-select.git`
 react-slick | `0.14.4` | `git+https://github.com/akiran/react-slick.git`
 react-tappable | `0.8.4` | `git+https://github.com/JedWatson/react-tappable.git`
 react-timesheet | `0.1.0` | `git+https://github.com/yuanyan/react-timesheet.git`
 react-tooltip | `3.2.1` | `git+https://github.com/wwayne/react-tooltip.git`
 react-virtualized | `8.0.11` | `git+https://github.com/bvaughn/react-virtualized.git`
 react-waypoint | `3.1.2` | `git+https://github.com/brigade/react-waypoint.git`
 reactcss | `1.0.8` | `git+https://github.com/casesandberg/reactcss.git`
 reactstrap | `3.2.2` | `git+ssh://git@github.com/reactstrap/reactstrap.git`
 screenfull | `3.0.2` | `git+https://github.com/sindresorhus/screenfull.js.git`
 shortid | `2.2.6` | `git+https://github.com/dylang/shortid.git`
 whatwg-fetch | `1.0.0` | `git+https://github.com/github/fetch.git`
 material design icons | | `https://github.com/google/material-design-icons`
 ionicons | | `https://github.com/driftyco/ionicons.git`













 # Media Query



 ### import the component modules

 ```js
 import {
     XXS,
     XS,
     S,
     L,
     XL,
     XXL
 } from '../../UI/MediaLayout.js';

 ```


 ## Using the Components

 ### `XXS`
 > Show content for extra small screens . `smartphones, portrait iPhone, portrait 480x320 phones (Android)`

 ```html
 <XXS>
   <div> This Content </div>
 </XXS>
 ```


 > Hide content for extra small screens . `smartphones, portrait iPhone, portrait 480x320 phones (Android)`

 ```html
 <XXS hide>
   <div> This Content </div>
 </XXS>
 ```
 -------
 ### `XS`
 > Show content for small screens . `smartphones, Android phones, landscape iPhone`

 ```html
 <XS>
   <div> This Content </div>
 </XS>
 ```

 > Hide content for small screens . smartphones, Android phones, landscape iPhone

 ```html
 <XS hide>
   <div> This Content </div>
 </XS>
 ```

 -------
 ### `S`

 > Show content for medium screens . `portrait tablets, portrait iPad, e-readers (Nook/Kindle), landscape 800x480 phones (Android)`

 ```html
 <S>
   <div> This Content </div>
 </S>
 ```


 > Hide content for medium screens . `portrait tablets, portrait iPad, e-readers (Nook/Kindle), landscape 800x480 phones (Android)`

 ```html
 <S hide>
   <div> This Content </div>
 </S>
 ```
 -------

 ### `L`
 > Show content for large screens . `tablet, landscape iPad, lo-res laptops ands desktops`

 ```html
 <L>
   <div> This Content </div>
 </L>
 ```

 > Hide content for large screens . `tablet, landscape iPad, lo-res laptops ands desktops`

 ```html
 <L hide>
   <div> This Content </div>
 </L>
 ```


 -------
 ### `XL`

 > Show content for big screens . `big landscape tablets, laptops, and desktops`

 ```html
 <XL>
   <div> This Content </div>
 </XL>
 ```

 > Hide content for big screens . `big landscape tablets, laptops, and desktops`

 ```html
 <XL hide>
   <div> This Content </div>
 </XL>
 ```

 -------
 ### `XXL`

 > Show content for very big screens .` hi-res laptops and desktops`

 ```html
 <XXL>
   <div> This Content </div>
 </XXL>
 ```


 > Hide content for very big screens .` hi-res laptops and desktops`

 ```html
 <XXL hide>
   <div> This Content </div>
 </XXL>
 ```
