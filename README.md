Autofac.iOS
===========

An Autofac build for iOS

Get it on [nuget](https://www.nuget.org/packages/Autofac.iOS/)

```
PM> Install-Package Autofac.iOS -Pre
```

Release Notes
  * Rebuilt against the iOS library type
  * No support for Default Values in constructor parameters (includes Value types)
    * Caused by lack of support in Mono/iOS for "Expression.Default"
  * No support for Factory Generator where there are duplicate input types
    * Caused by lack of support in Mono/iOS for "Expression.Throw"
  * No support for Metadata
    * Caused by lack of support in Mono/iOS for "Expression.Variable" and "Expression.Assign"
  * RegisterOpenGeneric may fail to resolve if types are not predetermined

