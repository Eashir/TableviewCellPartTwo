## TableviewCellPartTwo

<br>

Lets keep our `Second Horizontal Stackview` with the time labels. We'll set its `Alignment` to `Center` and its `Distribution` to Equal Spacing. `Spacing` will be 36. Make sure that each of the 4 vertical stackviews within it also have an `Alignment` of `Center`

We'll begin with our `ProfileImageView`. 

1. Set it to `40` width and `40` height.
2. Give it a `top space` and `trailing` constraint to the superview as `16`
3. We can also provide it with an aspect ratio of `1:1`
4. Make a copy of this for the `Birthday` ImageView.
5. Set its height + width to `30`
6. Hold `control` and drag from the `Birthday` ImageView to our `Profile` ImageView to select `Center Vertically`
7. Now give it a trailing constraint of `16` to the superview


1. Add a label, we'll call it `Name` label, with font size `20`
2. Set its `height` to `>=20`
3. Set its `leading` constraint as `16` to the `ProfileImageView`
4. Set its `trailing` constraint as `8` to the `BirthdayImageView`
5. Lets make a copy of this label, call it `Subtitle` Label with font size `14`
6. Hold control and drag from the `Subtitle` label to the `Name` label to set its **Align Leading** constraint to `>=4`
3. Set the `trailing` space of `Subtitle` Label to the superview as `189`
4. Set the `top` space aka vertical spacing constraint of `Subtitle` label to our `Name` label as `4`

We'll now make our line separator aka `Line` View
1. Make a `view`
2. Drag it to under all of our UI elements that we have so far
3. Change the color black or your preferred line separator color
4. Set its height to `1`
5. Set its `trailing` and `leading` constraints to `8`

Finally, we now simply
1. Go to our `Second Horizontal StackView`
2. Set its *Vertical* `Content Hugging Priority` to `250` instead of 251
3. Give it a height of `40.67`
4. Set its `top` space constraint to our Line View as `24`
5. Width as <= `240`
6. `Trailing` and `Leading` constraints to the superview as <= 32
7. `Bottom` space as `0` to the `superview`


