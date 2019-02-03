# Flutter/Dart Tips

## Monthly Tip Article

This article contains the Tips that I have wirtten over here.

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
