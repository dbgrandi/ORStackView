# ORStackView CHANGELOG

## Next

* Fixed crash when setting ORStackView.bottomMarginHeight without any child views on iOS8 - @dblock
* Defaults to having a bottom constraint, I have _no idea_ why I didn't make this default. - @orta1
* More inline documentation - @orta
* Update FBSnapshotTestCase and Expecta+Snapshots to fix Xcode6 testing. - @dbgrandi

## 1.2.0

* Added ORSplitStackView - @1aurabrown
* Removes stale constraints with tag ordering at runtime - @1aurabrown
* Support for resizable height / margin constraings - @1aurabrown

## 1.1.0

* Allow ORStackScrollViews to be created via nibs - @kylef
* Use toplayoutguide in ORStackViews - @kylef

## 1.0.0

* Stacking views
* Stacking views that uses view tags to automatically set the order
* UIScrollView subclass that handles having a stack set up for you
* API for UIViewControllers
