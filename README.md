# SLPopupViewController
This library is used for showing popupViewController. Compatible with swift 2.0, iOS 9
SLPopupViewController
A UIViewController Category to display a ViewController as a popup with different transition effects.
Written by Nguyen Duc Hoang, September 2015.

##Installation

Open in Xcode7 SWIFT project. Also you need to add the QuartzCore-Framework to your project.

##Usage

First you have to import the category

Simply use presentPopupViewController:animationType, f.e.:

let myPopupViewController:MyPopupViewController = MyPopupViewController(nibName:"MyPopupViewController", bundle: nil)
myPopupViewController.delegate = self
self.presentpopupViewController(myPopupViewController, animationType: animationType, completion: { () -> Void in
})
        
to dismiss the popup, use dismissPopupViewControllerWithanimationType

self.dismissPopupViewController(.Fade)
see the demo for more detailed examples

##Demo

You can open the SLPopupViewControllerDemo demo project in Xcode and run it on your iPhone as well as in the Simulator.
<img src="https://raw.github.com/sunlight3d/SLPopupViewController/master/assets/pic1.png" width="283" height="501"/>
<img src="https://raw.github.com/sunlight3d/SLPopupViewController/master/assets/pic2.png" width="283" height="500"/>
