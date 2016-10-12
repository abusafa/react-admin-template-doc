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
