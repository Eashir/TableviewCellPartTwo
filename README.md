## TableviewCellPartTwo

<br>
<img width="1280" alt="Screen Shot 2024-01-12 at 8 53 42 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/ee910935-3c32-4a78-aa35-2bbedadb298d">

<br><br>
Initialize a stack view. Theres a '+' icon at the top to the right of where it says "Running CustomTableViewCell"

<br>
<br>
<img width="236" alt="Screen Shot 2024-01-12 at 9 18 46 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/89088acd-bd2b-43a5-b991-71ad398ee3a9">
<br><br>

1. Rename the main stackview
2. Make axis vertical
<br>
3. Set Distribution to 'Fill Equally'
   This is because we have two equal halves in the UI that we're going for
<img width="260" alt="Screen Shot 2024-01-12 at 9 23 58 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/38aee065-9347-458e-90e2-8d2db2a2ba28">

<br><br>
<img width="380" alt="Screen Shot 2024-01-12 at 9 23 22 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/1dbc0958-f65e-4e74-9f26-811706e8cb85">

4. Select the main stack view (*in our case its the Main Vertical Stack View*)
5. Click on the constraints button
6. Enter 0 in all 4 of the spaces
7. Hit the "Add 4 Constraints" button
This will make sure the main stack view takes up all the space in the cell
<br<br><br>

Now we're at the part where it can get a little confusing so focus up! 

1. Add 2 more stackviews in the main stackview with a horizontal axis
2. In the upper horizontal stackview, which I labeled First Horizontal Stack View, add a vertical stackview
3. In this vertical stackview, add both of your text labels 'Cameroon' and 'Turns 30...'

  Heres what it looks like
<img width="1007" alt="Screen Shot 2024-01-12 at 9 31 33 PM" src="https://github.com/Eashir/TableviewCellPartTwo/assets/20934684/302aad0d-8872-4b5d-9057-fac533e68d20">

  
4. In the Second Horizontal Stack View, add a vertical stackview
5. In this vertical stackview, add the '364' and 'Days' labels
6. You can copy this stackview and post it 3 more times for the rest of the time labels
7. Add your images in the First Horizontal Stackview
8. Give your images an aspect ratio of 1:1
...and wa-la! We've setup our stackviews!
