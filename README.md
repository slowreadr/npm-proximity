version 0.1.0

create a grid engine that will allow for easy extension


Todo:
mixins ->
	.make-container(
		@gutters: @default,								-> padding lft & rt to config default
		@max-width: @default,							-> max-width to config default
		@align: center,									-> align object horizontal center
		@bg-color: @green,								-> set objects background color
		@direction: rtl,								-> reverse content direction
	);

	.style-object(
		@gutters: 0.625em,								-> set gutters
		@inset: 5em,									-> inset object within content flow
		@bg-color: @greyscale(18),						-> set background color for object

	);
	.heading(
		@font-size: 2.25,								-> 225% objects base font size
		@color: @white,									-> text color of @white
		@align: left,									-> align text left

	);
