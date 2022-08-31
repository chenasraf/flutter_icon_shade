# Flutter Icon Shade

> This package has been deprecated and renamed `flutter_icon_shadow`. Please use that package
> instead, which has additional features and is more maintained.
> [Package page](https://pub.dev/packages/flutter_icon_shadow)

Flutter Icon shadow

Forked from [icon_shadow](https://github.com/mehrtarh/flutter_icon_shadow) for
null safety.

![sample](https://github.com/chenasraf/flutter_icon_shade/blob/master/sample.PNG?raw=true)

## How to use

### 1. Add dependencies to pubspec.yaml

```yaml
flutter_icon_shade: ^2.0.2
```

### 2. Add icons

```dart
Row(
    mainAxisAlignment: MainAxisAlignment.center,
    children: <Widget>[
        IconShade(
            Icon(
                Icons.lightbulb_outline,
                color: Colors.lightBlueAccent,
                size: 36,
            ),
        ),
        IconShade(
            Icon(
                Icons.lightbulb_outline,
                color: Colors.lightBlueAccent,
                size: 36,
            ),
            shadowColor: Colors.lightBlueAccent.shade100,
        ),
        IconShade(
            Icon(
                Icons.lightbulb_outline,
                color: Colors.lightBlueAccent,
                size: 36,
            ),
            showShadow: false,
        ),
    ],
)
```
