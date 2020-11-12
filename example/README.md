# modular_permission_location_example

Location permission plugin to be used with the [Modular App Permissions plugin](https://github.com/uptech/modular_app_permissions).
If you are interested in contributing, checkout the [CONTRIBUTION.md](https://github.com/uptech/modular_app_permissions/CONTRIBUTION.md) in the main Modular App Permissions repo.

## Plugin Information

This plugin is not intended to be used on its own. It is designed to be used in the [Modular App Permissions
plugin](https://github.com/uptech/modular_app_permissions). Using this plugin by itself will work
but the developer is responsible for building the Dart interface.  

## Permission Definition

*Android*: This plugin automatically includes the ` <uses-permission android:name="android.permission.ACCESS_FINE_LOCATION"/>`.
*iOS*: You _MUST_ include the proper NSUSAGE key in your `info.plist`. Failure to do so will result in 
improper use of this library. 
- [NSLocationAlwaysUsageDescription](https://developer.apple.com/documentation/bundleresources/information_property_list/nslocationalwaysusagedescription)
- [NSLocationWhenInUseUsageDescription](https://developer.apple.com/documentation/bundleresources/information_property_list/nslocationwheninuseusagedescription)
- [NSLocationAlwaysAndWhenInUseUsageDescription](https://developer.apple.com/documentation/bundleresources/information_property_list/nslocationalwaysandwheninuseusagedescription)


## About <img src="http://upte.ch/img/logo.png" width="180">

`modular_permission_location` is maintained and funded by [UpTech Works, LLC][uptech], a
software product, design & development consultancy.

We love open source software. See [our other projects][community] or
[hire us][hire] to design, develop, and grow your product.