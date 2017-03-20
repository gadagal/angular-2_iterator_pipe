# angular-2_iterator_pipe
A Simple for loop iterator module for angular 2

Usage:

To use it in a component, add iterator module to that components module

For example if you want to use iterator in app component, just import iterator module like this;

import {IteratorModule} from '%path_to_the_module%iterator_pipe.module';

and in the NgModule decorator;

@NgModule({

  imports: [
    ..
    ..
    IteratorModule,
    ..
    
  ],
  
  And you are good to go. In app component template;
  
  <div *ngFor="let i of %Number of iteration % | iteratorPipe" ...>
