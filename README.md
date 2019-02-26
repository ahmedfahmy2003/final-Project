# final-Project
You Decide Udacity Course final project

# overview 
Virtual Tourist is an iOS app that allows users to visit virtual locations by adding pins to a MKMapView.
Once a user taps a pin the app fetches photos from Flickr for that location.

# New Features
The App checks for internet connection before fetching images from Flickr and display alert for users.

# Swift and Xcode versions
it is built using XCode Version 10.1 (10B61) with Swift 4

# App Specification
This app allows users specify travel locations around the world, and create virtual photo albums for each location.
The locations and photo albums will be stored in Core Data.

the App will have 2 view scenes:

1 - MapView Scene
shows the map and allows user to drop pins around the world. As soon as a pin is dropped photo data for the pin location is fetched from Flickr.
The actual photo downloads occur in the CollectionController.

2- CollectionView scene
allow users to download photos and edit an album for a location. Users can create new collections and delete photos from existing albums.

# License
Copyright (c) 2019 Ahmed Fahmy (ahmed.fahmy.hassan@gmail.com)
Permission is hereby granted, free of charge, to any person obtaining a copy of this software 
to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software
