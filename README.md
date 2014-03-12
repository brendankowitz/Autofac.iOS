Autofac.iOS
===========

An Autofac build for iOS

Get it on [nuget](https://www.nuget.org/packages/Autofac.iOS/)

```
PM> Install-Package Autofac.iOS -Pre
```

Release Notes
  * Rebuilt against the iOS library type
  * Removed support for Default Values in constructor parameters (includes Value types)
  * No support for Factory Generator where there are duplicate input types
  * No support for Metadata
  * RegisterOpenGeneric may fail to resolveif types are not predetermined

