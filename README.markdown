Some code snippets for Xcode 4 that I find useful.

Based on [*Kendall Helmstetter Gelner's*](http://stackoverflow.com/users/6330/kendall-helmstetter-gelner) example on [*StackOverflow*](http://stackoverflow.com/questions/5303374/how-do-i-create-custom-text-macros-in-xcode-4).

1. MyTest - original example from StackOverflow. Type "nurse" and you will get "NSLog(@"Hello Nurse %@", <#Thing#>);" 
2. NSLog - based on the original NSLog macro from older versions of XCode (log control+.). 
Type l and you will get NSLog(@"<#Comment#>");
3. VarLog - Just an NSLog statement that lets you echo a variable and specify the name & type also. 
NSLog(@"<#Variable Name#>: %<#Variable Type#>", <#Variable#>);