## TableviewCellPartTwo

<br>

Lets keep our `Second Horizontal Stackview` with the time labels. We'll set its `Alignment` to `Center` and its `Distribution` to Equal Spacing. `Spacing` will be 36. Make sure that each of the 4 vertical stackviews within it also have an `Alignment` of `Center`

<img width="1000" alt="Screen Shot 2024-01-16 at 4 25 07 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/f5a8c304-5657-4064-b716-9b6edfa0779c">

<br><br><br>
We'll begin with our `ProfileImageView`. 


1. Set it to `40` width and `40` height.
2. Give it a `top space` and `trailing` constraint to the superview as `16`
3. We can also provide it with an aspect ratio of `1:1`
<img width="600" alt="Screen Shot 2024-01-16 at 4 30 03 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/48e8e092-3ffe-49be-9102-d55e89d42b5e">



<br><br>
1. Make a copy of this for the `Birthday` ImageView.
2. Set its height + width to `30`
3. Hold `control` and drag from the `Birthday` ImageView to our `Profile` ImageView to select `Center Vertically`
4. Now give it a trailing constraint of `16` to the superview
5. We can also give it a 1:1 ratio

<img width="606" alt="Screen Shot 2024-01-16 at 6 56 29 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/15608983-60b2-4287-8f95-a236f8edd07e">
<img width="1280" alt="Screen Shot 2024-01-16 at 6 49 43 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/8720d0af-982a-445f-877d-f38257b3a42b">


<br><br>
1. Add a label, we'll call it `Name` label, with font size `20`
2. Set its `height` to `>=20`
3. Set its `leading` constraint as `16` to the `ProfileImageView`
4. Set its `trailing` constraint as `8` to the `BirthdayImageView`
5. Hold control and drag from the `Name` label to `ProfileImageView` to set its `Align Top` constraint
6. Set its `Lines` property to `0`
   
   <img width="607" alt="Screen Shot 2024-01-16 at 6 54 17 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/48cad639-5e7a-4f4a-ab6f-296676c69063">
<br><br>  <br><br>  
   Now with `Name` label selected, go to Editor and select `SizeToFit`
<img width="1280" alt="Screen Shot 2024-01-16 at 7 02 12 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/4da07702-fcbe-4b41-ba04-70d1cd412a96">

   

<br><br><br><br>  
1. Lets make a copy of this label, call it `Subtitle` Label with font size `14`
2. Hold control and drag from the `Subtitle` label to the `Name` label to set its **Align Leading** constraint to `>=0`
3. Set the `trailing` space of `Subtitle` Label to the superview as `189`
4. Set the `top` space aka vertical spacing constraint of `Subtitle` label to our `Name` label as `4`
   
<img width="651" alt="Screen Shot 2024-01-16 at 5 45 22 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/21f22e93-f7bf-4ad6-b640-8a566678431f">

   
<br><br>
We'll now make our line separator aka `Line` View
1. Make a `view`
2. Drag it to under all of our UI elements that we have so far
3. Change the color black or your preferred line separator color
4. Set its height to `1`
5. Set its `trailing` and `leading` constraints to `8`

<img width="639" alt="Screen Shot 2024-01-16 at 6 21 20 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/3d69634b-1d82-4649-9b74-39864120c4e7">

<br><br>
Finally, we now simply
1. Go to our `Second Horizontal StackView`
2. Set its *Vertical* `Content Hugging Priority` to `250` instead of 251
3. Give it a height of `40.67`
4. Set its `top` space constraint to our Line View as `24`
5. Width as <= `240`
6. `Trailing` and `Leading` constraints to the superview as <= 32
7. `Bottom` space as `0` to the `superview`

<img width="628" alt="Screen Shot 2024-01-16 at 6 31 29 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/50f97a84-06b8-46a6-bcac-2ff98259701d">

To make our imageviews into circles, we can link it into our PersonTableViewCell and put this code 

```
override func layoutSubviews()  {

    self.ProfileImageView.layer.cornerRadius = self.yourImageView.bounds.height/2
    self.ProfileImageView.clipsToBounds = true
}
```

[Like this] (https://github.com/Eashir/TableviewCell/blob/main/README.md)
And there you have it! Place your desired fonts, colors, and images and you're all-set!


