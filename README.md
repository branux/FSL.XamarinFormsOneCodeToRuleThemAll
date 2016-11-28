# FSL.XamarinFormsOneCodeToRuleThemAll

**Xamarin Forms: one code to rule them all**

There a lot of mobile devices for three platforms:
- Android. 90% of devices, Java programming language.
- iOS. 9% of devices, Objective-C programming language. You will need a MAC.
- Windows Phone. 1% of devices, C# programming language.

Let’s face a major problem:

*"I am a C# developer and I want to create a mobile app for all platforms but I don’t program in Objective-C or Java and I don’t want to spend time and money with that. How Xamarin Forms could help me?"*

OK, Xamarin is a C# framework to create mobile app for iOS and android using C# language. OK ok ok, you can create mobile app for windows phone too.

You can use Xamarin.iOS  to create mobile user interface for iOS and use Xamarin.Droid to create mobile user interface for Android.

You just need to install Xamarin plugin for Visual Studio on Windows or use Xamarin Studio IDE on Mac.

Using Xamarin.Droid or Xamarin.iOS for mobile user interface you will need to write two codes: one for android and another one for iOS. There are some small parts of code you can share between those projects like database access and business logic.

They call that of traditional Xamarin aproach:

![traditional Xamarin aproach](https://fabiosilvalima.files.wordpress.com/2016/11/xamarin-traditional.png)

*"Oh gosh! Write two mobile user interfaces?? Is there a another or a better way?"*

Yes! Xamarin Forms!

You can use Xamarin.Forms to write only one code and run your app in iOS and Android. Xamarin Forms is an abstraction that works together with Xamarin.iOS and Xamarin.Droid. If you create a mobile user interface in Xamarin Forms you don't need to create the same user interface on Xamarin.Droid or Xamarin.iOS. The mobile user interface is shared between them.

They call that of Xamarin Forms aproach:

![Xamarin Forms aproach](https://fabiosilvalima.files.wordpress.com/2016/11/xamarin-forms.png)

<em>"I don't believe, it's magic, just one code to rule them all!"</em>

Alright, take it easy. Is not that simple. Xamarin Forms helps a lot, but some things you will still need an adjustment only for iOS or Droid projects. But, yes, a lot of code are shared between those projects and helps a lot.

Anyway, in my opinion it's still better using Xamarin Forms than learn Java or Objective-C and write two distinct mobile app.  With Xamarin Forms you share backend methods, classes and off course the user interface.

*"So, how Xamarin Forms works?"*

When you create a Xamarin Forms project (Cross-mobile) using Visual Studio, it creates a solution file with three Xamarin projects:

1 - Portable project (Xamarin Forms)
2 - Android project (Xamarin.Droid)
3 - iOS project (Xamarin.iOS)

Solution structure:

![Solution structure](https://fabiosilvalima.files.wordpress.com/2016/11/xamarinproject.png)

Just for understanding, imagine Xamarin.Forms like a reusable DLL and Xamarin.iOS and Xamarin.Droid projects like web projects that references that reusable DLL. In web programming, you deploy the web project and for Xamarin it's the same, you deploy Xamarin.Droid and Xamarin.iOS for respective devices.

You can download my sample Xamarin Forms project:
[FSL.ButtonBorderAndRadiusInXamarinForms][1]

If you want to install and configure Xamarin in your Visual Studio check my article:
[Visual Studio 2015 Xamarin Forms Install and Config][2]

Good luck!


References:
---

- Visual Studio 2015 Xamarin Forms Install and Config [check here][3];

Licence:
---

- Licence MIT


[1]:https://github.com/fabiosilvalima/FSL.ButtonBorderAndRadiusInXamarinForms
[2]: https://fabiosilvalima.wordpress.com/2016/11/10/visual-studio-2015-xamarin-forms-install-and-config/
[3]:https://fabiosilvalima.wordpress.com/2016/11/10/visual-studio-2015-xamarin-forms-install-and-config/
