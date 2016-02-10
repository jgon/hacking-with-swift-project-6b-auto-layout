# Hacking with Swift - Project 6b - Auto layout

Using auto layout constraint programmatically.

## Topics covered

- Using the Visual Format Language (VFL) to define constraints.
- ```view.addConstraints(NSLayoutConstraint.constraintsWithVisualFormat(...))``` converts VFL into an array of constraints.
- Using ```==``` (equal) and ```>=``` (greater than or equal) constraints.
- Using ```metrics``` in constraints.
- Using priority (```999```) in constraints to have the labels height adapt when showing in landscape.
- ```"V:|[label1(labelHeight@999)]-[label2(label1)]-[label3(label1)]-[label4(label1)]-[label5(label1)]->=10-|"```
- Hiding the status bar using ```prefersStatusBarHidden```.

## Prequisites

- Xcode 7.2.1
- Swift 2.x
- iOS 9.2
