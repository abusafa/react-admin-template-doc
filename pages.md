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
