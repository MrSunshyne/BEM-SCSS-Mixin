BEM-SCSS-Mixin
==============

A very good mixin originally authored by Mark Mintel.

## Usage 

```SCSS

@include b(test) {
   background: red;
   @include m(modifier) {
       color: blue;
       @include e(subelement) { 
           background: gray;
       }
   }
}
```
