# Work in progress

# DATATableController

## Usage

```objc
NSFetchRequest *fetchRequest = [[NSFetchRequest alloc] initWithEntityName:@"Task"];
fetchRequest.sortDescriptors = @[[NSSortDescriptor sortDescriptorWithKey:@"title" ascending:YES]];

DATATableController *controller = [[DATATableController alloc] initWithFetcher:self.fetcher ForEntity:@"User" fetchRequest:fetchRequest];
```

## Author

Elvis Nuñez, elvisnunez@me.com

## License

**DATATableController** is available under the MIT license. See the LICENSE file for more info.
