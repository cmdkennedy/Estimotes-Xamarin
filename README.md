Estimotes-Xamarin
=================

**OBSOLETE**: This branch is based on an older version of Estimote binding which was originally distributed via the Xamarin Component Store. Distribution has since switched to NuGet. 

---

This is a Java Library binding for the [Estimotes SDK for Android](https://github.com/Estimote/Android-SDK). I've also ported the Android sample project to show some of the features in action. It's not a 1-to-1 port, I've made some changes along the way.

Many thanks to James Montemagno for updating this to 1.0.4.2 of Estimotes.

There are two projects:

* `Estimotes.Binding.Droid` - this is the Java Binding library. You can rebuild the binding at the command line using `rake`. 
* `Estimotes.Droid` - this is a sample project showing how to use the Estimotes SDK for Android in Xamarin.Android project. 

Installation
------------

The binding is [available via NuGet](https://www.nuget.org/packages/Estimotes-Xamarin/) :

    PM> Install-Package Estimotes-Xamarin


What About iOS?
---------------

Greg Shackles has a [binding for Xamarin.iOS](https://github.com/gshackles/Estimote-iOS-Xamarin). 


