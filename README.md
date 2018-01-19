# Create new angular project

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.5.
> run `$ng new ng-material`

## Install angular material packages

run `$npm install @angular/material @angular/cdk --save`

## Install animation package

Run `$npm install @angular/animations --save` 

## import animation package

open `src/app/app.module.ts` 
> import {BrowserAnimationsModule} from '@angular/platform-browser/animations';

>@NgModule({
>  ....
>
>  imports: [
>    BrowserModule,
>    BrowserAnimationsModule
>    
>  ],
>  ....
> })

## create material module

+ material.module.ts
> import {MatButtonModule} from '@angular/material/button';

## import materialmodule to app.module.ts

>import { MaterialModule } from './material.module';
>@NgModule({
>  ....
>
>  imports: [
>    BrowserModule,
>    BrowserAnimationsModule,
>    MaterialModule
>  ],
>  ....
> })
## install hammerjs package

> npm install --save hammerjs