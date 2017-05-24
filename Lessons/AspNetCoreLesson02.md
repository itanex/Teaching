# AspNetCore Lesson 02

### Data Binding
Take the example we went through and create a new Complex Data Binding using the following models

```
Product
    Id: number
    Name: string
    Price: number
    Origin: Company
Company
    name: string
    country: string
```

#### REQUIREMENTS
* Create a WebAPi controller that stores the data in a static list
* Use angular-resource to GET or POST(save)
* Single page experience no UI-Router
* Present a table of all current products at the top of the screen
* Present a form below the table to create a new product
* No need for fancy formating
* No need to create multiple JS file, use only one
   * No need for separate modules either

####  STRETCH GOALS
1. Make it look nice, Use Bootstrap or Material Design to style the page
2. Make it multiple Pages
3. [LIFT](https://github.com/johnpapa/angular-styleguide/blob/master/a1/README.md#application-structure-lift-principle) the single js file