# DATATableController

## Usage

```objc
NSFetchRequest *fetchRequest = [[NSFetchRequest alloc] initWithEntityName:@"Task"];
fetchRequest.sortDescriptors = @[[NSSortDescriptor sortDescriptorWithKey:@"title" ascending:YES]];

DATATableController *controller = [[DATATableController alloc] initForEntity:@"User" fetchRequest:fetchRequest];

// Networking + Sync + DATASource
```

## Installation

**DATATableController** is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'DATATableController'
```

## Author

Elvis Nuñez, elvisnunez@me.com

## License

**DATATableController** is available under the MIT license. See the LICENSE file for more info.
