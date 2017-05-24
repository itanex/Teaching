# Routing, Services and $http Oh My!

#### COMPLETE THE FOLLOWING FOR 3/15
* Practice Lab for AngularJS Routing - Master/Detail Views
* Practice Lab for AngularJS Ajax - Using the $http Service
* Create a simple Angular Application that presents the following:
   * A field of text that shows a 'fortune cookie' string
   * A button that gets a new 'fortune cookie' string
   * Use an Angular Controller with a dependency on an Angular Service which implements the following interface:

```JavaScript
export interface IFortuneCookieService {
	getRandomFortune(): string;
}
```

* The service must pull the list of 'FortuneCookie' strings from a json file on the server. 
* **DO NOT** store the data in your service.