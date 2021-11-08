# underscore before the file name it is show that the file not convert into the CSS

# if Box is my class and button inside it and we perform the hover we can write 

 .Box:hover {
    background-color: black;
  } 

  or 
  it is only use inside the nested Box
  &:hover{
      background-color: black:
  }

# it is in styles.scss
<!-- a {
  margin-bottom: 10px;
  &:nth-child(odd) {
    @include link(red);
  }
  &:nth-child(even) {
    @include link(blue);
  }
} -->

# it is in _mixins.scss
<!-- @mixin link($color) {
  text-decoration: none;
  display: block;
  color: $color;
} -->

----------------------------------------------------------------

<!-- a {
  margin-bottom: 10px;
  &:nth-child(odd) {
    @include link("odd");
  }
  &:nth-child(even) {
    @include link("even");
  }
} -->

<!-- 
@mixin link($word) {
  text-decoration: none;
  display: block;
  @if $word == "odd"{
  color: blue;
   }
   @else {
     color: green;
   }
} -->

--------------------------------------------

# we can do extend by % 

------------------------------------------------

# box-shadow:         3px 3px 5px 6px #ccc;

<!-- 1 The horizontal offset of the shadow, positive means the shadow will be on the right of the box, a negative offset will put the shadow on the left of the box.
2 The vertical offset of the shadow, a negative one means the box-shadow will be above the box, a positive one means the shadow will be below the box.
3 The blur radius (optional), if set to 0 the shadow will be sharp, the higher the number, the more blurred it will be.
4 The spread radius (optional), positive values increase the size of the shadow, negative values decrease the size. Default is 0 (the shadow is same size as blur).
5 Color -->