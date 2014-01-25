#ResponsiveGridz

##How to use

1.  Include this file at the beginning of your main design file using the SASS syntax.

	ex :
	
	```scss
	@import "responsiveGridz";
	```

2.  If your design has a fix max-width, use the `$baseWidth` var to set the width of your main container.

	ex :
	
	```scss
	body{
		width: $baseWidth;
	}
	```


3.  Use the `grids_columns()` and `gridz_gutter()` functions to set flexible widths and margins to your box elements.

	```scss
	gridz_columns( $cols, $parent )
	gridz_gutter( $parent )
	-------------------------------------------------
	$cols = amount of columns the element has to take
	$parent = amount of columns of the parent element
	```

4.  Add media queries on your main-container

5.  Enjoy the flexible gridz on your child-elements !
