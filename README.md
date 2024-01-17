## TableviewCellPartTwo

<br>

Lets keep our `Second Horizontal Stackview` with the time labels. We'll set its `Alignment` to `Center` and its `Distribution` to Equal Spacing. `Spacing` will be 36. Make sure that each of the 4 vertical stackviews within it also have an `Alignment` of `Center`

<img width="1000" alt="Screen Shot 2024-01-16 at 4 25 07 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/f5a8c304-5657-4064-b716-9b6edfa0779c">

<br><br><br>
We'll begin with our `ProfileImageView`. 


1. Set it to `40` width and `40` height.
2. Give it a `top space` and `trailing` constraint to the superview as `16`
3. We can also provide it with an aspect ratio of `1:1`

<img width="600" alt="Screen Shot 2024-01-16 at 4 30 03 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/fb965dd4-a194-4214-b0d0-d7dc15a5c66e">
   
<img width="1280" alt="Screen Shot 2024-01-16 at 6 49 43 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/8720d0af-982a-445f-877d-f38257b3a42b">


<br><br>
1. Make a copy of this for the `Birthday` ImageView.
2. Set its height + width to `30`
3. Hold `control` and drag from the `Birthday` ImageView to our `Profile` ImageView to select `Center Vertically`
4. Now give it a trailing constraint of `16` to the superview
5. We can also give it a 1:1 ratio
<img width="606" alt="Screen Shot 2024-01-16 at 6 56 29 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/15608983-60b2-4287-8f95-a236f8edd07e">


<br><br>
1. Add a label, we'll call it `Name` label, with font size `20`
2. Set its `height` to `>=20`
3. Set its `leading` constraint as `16` to the `ProfileImageView`
4. Set its `trailing` constraint as `8` to the `BirthdayImageView`
5. Hold control and drag from the `Name` label to `ProfileImageView` to set its `Align Top` constraint
   <img width="607" alt="Screen Shot 2024-01-16 at 6 54 17 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/48cad639-5e7a-4f4a-ab6f-296676c69063">

<br><br>  
7. Lets make a copy of this label, call it `Subtitle` Label with font size `14`
8. Hold control and drag from the `Subtitle` label to the `Name` label to set its **Align Leading** constraint to `4`
3. Set the `trailing` space of `Subtitle` Label to the superview as `189`
4. Set the `top` space aka vertical spacing constraint of `Subtitle` label to our `Name` label as `4`

   
<br><br>
We'll now make our line separator aka `Line` View
1. Make a `view`
2. Drag it to under all of our UI elements that we have so far
3. Change the color black or your preferred line separator color
4. Set its height to `1`
5. Set its `trailing` and `leading` constraints to `8`

<br><br>
Finally, we now simply
1. Go to our `Second Horizontal StackView`
2. Set its *Vertical* `Content Hugging Priority` to `250` instead of 251
3. Give it a height of `40.67`
4. Set its `top` space constraint to our Line View as `24`
5. Width as <= `240`
6. `Trailing` and `Leading` constraints to the superview as <= 32
7. `Bottom` space as `0` to the `superview`


