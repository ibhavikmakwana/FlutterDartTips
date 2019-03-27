# Flutter/Dart Tips

### 8. Cascade Notation - Method Chaining on Steroids :pill::syringe:
`Cascades Notation (..)` allows to chain a sequence of operations on same object. In addition, fields (data-memebers) can be accessed using the same.

[Open in DartPad :dart:](https://dartpad.dartlang.org/a93316aa779a2e0dd1993ae9a3464731)

<img src="./tips/cascade_notation.png" width=600 alt="Screenshot">

### 7. Want to set different Theme for a perticular widget ?

Just wrap the widget with the `Theme` Widget and pass the `ThemeData()`.

<img src="./tips/ThemeWidgetExample.png" height="550" alt="Screenshot"/>

## Monthly Tip Article (February 2019)

This article contains the Tips from February month that shared over here.

[#2 Flutter + Dart Tips](https://medium.com/flutter-community/2-flutter-dart-tips-f149ffe83381)

### 6. Use Ternary operator instead of the if else to shorter your Dart code.

Use below.

<img src="./tips/ternary.png" height="250" alt="Screenshot"/>

Instead of this.

<img src="./tips/if_else.png" height="250" alt="Screenshot"/>

### 5. Want to run task periodically in Dart?

What about using `Timer.periodic`
It will create a repeating timer, It will take a two argument one is `duration` and second is `callback` that must take a one Timer parameter.

<img src="./tips/timer.png" height="250" alt="Screenshot"/>

You can cancle the timer using the `timer.cancel()`.

### 4. Apply style as a Theme in a `Text` widget.
Check out below article for detail information about this tip.
[Apply style as a Theme in a `Text` widget](https://medium.com/flutter-community/flutter-apply-style-as-a-theme-in-a-text-widget-90268328bd23)

<img src="./tips/text_theme.png" height="250" alt="Screenshot"/>

## Monthly Tip Article (January 2019)

This article contains the Tips from January month that shared over here.

[#1 Flutter + Dart Tips](https://medium.com/flutter-community/1-flutter-dart-tips-830854c3a418)


### 3. Do not explicitly initialize variables to `null`.

Adding `= null` is redundant and unneeded.

<img src="./tips/avoid_init_null.png" height="250" alt="Screenshot"/>

### 2. Using `ListView.separated()`
Want to add the separator in your Flutter ListView?

Go for the
`ListView.separated();`

Best part about seprated is it can be any widget.😃

Check out the below image for the sample code.

<img src="./tips/ListViewSeprated.png" height="250" alt="Screenshot"/>

### 1. Using `null-aware operators`
While checking the null in the Dart, Use `null-aware operators` help you reduce the amount of code required to work with references that are potentially null.

<img src="./tips/DartTip_14-1-2019.png" height="250" width="250" alt="Screenshot"/>
