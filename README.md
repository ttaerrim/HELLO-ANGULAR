# HELLOANGULAR

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.0.6.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).

### Angular-typescript


type 지정
```typescript
let a : number = 10;
```
decorator, 상속, constructor, 접근 지정자
```typescript
@NgModule()
class App extend Parent{
  
    @Output() eventEmitter: any;
    
      // 멤버 변수에도 데코레이터 사용 가능
      
    constructor(private http: HttpClient) {
    
      // 접근 지정자를 통해 자동으로 매개변수를 통해 멤버 변수에 값 할당  
      
    }

}
```

component 생성
```cli
ng generate component header
```
