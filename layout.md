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
