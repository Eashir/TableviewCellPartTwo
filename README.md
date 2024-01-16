## TableviewCellPartTwo

<br>

Lets keep our `Second Horizontal Stackview` with the time labels. We'll set its `Alignment` to `Center` and its `Distribution` to Equal Spacing. `Spacing` will be 36. Make sure that each of the 4 vertical stackviews within it also have an `Alignment` of `Center`

We'll begin with our ProfileImageView. 

1. Set it to 40 width and 40 height.
2. Give it a top space and trailing constraint of 16
3. We can also provide it with an aspect ratio of 1:1
4. Make a copy of this for the birthday icon.
5. Set its height width to 30 and 


1. Add a textlabel, we'll call it `Name` label, with font size `20`
2. Set its `height` to `>=20`
3. Set its `leading` constraint as `16` to the `ProfileImageView`
4. Lets make a copy of this label, call it `Subtitle` Label with font size `14`
6. Hold control and drag from the `Subtitle` label to the `Name` label to set its **Align Leading** constraint to `>=4`
3. Set the trailing space of `Subtitle` Label to the superview as `189`
4. Set the top space aka vertical spacing constraint of `Subtitle` label to our Name label as `4`

We'll now make our line separator
1. Make a `view`
2. Change the color black or your preferred line separator color
3. Set its height to `1`
4. Set its trailing and leading constraints to `8`

Finally, we now simply
1. Go to our Second Horizontal StackView
2. Set its *Vertical* `Content Hugging Priority` to `250` instead of 251
3. 


