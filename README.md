# tpv.Angular
TPV front-end made in Angular
This is a front-end application made by me, presented as my Final Master Project.

The app needs this back-end application in order to works:
https://github.com/miw-upm/SPRING.tpv/releases/tag/tpv-1.0.0

My part includes the functionality that a worker of a shop needs on a daily basis.

Instructions:


* Install [NodeJS](https://nodejs.org/en/download/).


* Install Angular CLI:
```
npm install -g @angular/cli
```

If it's the first time you execute the applicaiton, you have to generate all the dependencies:

```
cd src/main/webapp/ng-app
npm install
```

Once you have generate the Angular files, you can run the app with the following command:

```
cd src/main/webapp/ng-app
npm start
```
To run the unit tests:
```
cd src/main/webapp/ng-app
npm run test
```

To run the end-to-end tests:
```
cd src/main/webapp/ng-app
npm run e2e
```