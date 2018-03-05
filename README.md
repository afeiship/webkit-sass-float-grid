# webkit-sass-float-grid
> Grid implement by float

## resources:
+ https://github.com/afeiship/generator-webkit-sassui
+ https://purecss.io/grids/

## usage:
```scss
@import 'node_modules/webkit-sass-float-grid/dist/webkit-sass-float-grid.scss';

$inGridResponsive:(
  span: auto,
  sm:567px,
  md:767px,
  lg:1023px,
)!default;

@include webkit-sass-float-grid($inGridResponsive, $inGridCount: 24, $inGridPrefix:'.g');
```
