## [1.0.4] - 27 Aug 2020

* Implement search.

## [1.0.3] - 22 Aug 2020

* Add show phone code option.

## [1.0.2] - 18 Aug 2020

* Add exclude countries option.  
Can be used to exclude(remove) one ore more country from the countries list
```Dart
showCountryPicker(
   context: context,
   exclude: <String>['KN', 'MF'], //It takes a list of country code(iso2).
   onSelect: (Country country) => print('Select country: ${country.displayName}'),
);
```

## [1.0.1] - 12 Aug 2020

* Add documentation.

## [1.0.0] - 11 Aug 2020

* Initial developers preview release.
