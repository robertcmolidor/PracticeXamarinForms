# PracticeXamarinForms
runs on Android api level23 android, a simple pcl playground to learn the things


all examples are code only.  no xaml

Clock is an example of using data binding and INotifyPropertyChanged from the xamarin forms documentation

Corners simply demonstrates sticking labels in corners

Keypad is an example of using ICommand to make buttons do stuff.  also translated from the xamarin forms mvvm documentation
  -this gave me a lot of challenge so it's notated all to hell.  just in case you're looking for that kind of thing
  
Names simple takes whatever you type in and presents it in a label

Stack1 is an example of a horizontal stacklayout

Stack3 is and example of a stack of grids

TwoWayBinding is an example of two way binding sliders to a color property which also updates labels and the color of a boxview. This is also taken from xamarin forms mvvm documentation but translated to code only

ViewBinding is an example of view to view binding.  a slider makes a label tumble.  

MultiSelect uses a stacklayout to select days of the week I'm calling a custom picker.  the selected days are displayed in a binded listview in the root page.  This example is using navigation page to allow for pushasync and popasync.  I tried to make this as generic as possible.  create the pickerViewModel, pass a dictionary of your itemslist in, and recieve the selected items back. you can also pass in a list of selected items so they are preselected when the picker loads
