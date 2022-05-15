
## Fix issues in flutter 3 
```

dependency_overrides:
  flare_flutter :
    git:
      url: https://github.com/mdpe-ir/Flare-Flutter
      path: flare_flutter
      ref: stable

```



## Null Safety
Preview of null safety is now available on pub.dev with version 3.0.0. Include it in your pubspec via:
```
  dependencies:
    flare_flutter: ^3.0.0-nullsafety.0
```

## Packages
There used to be two Dart packages provided in this repository. [flare_dart](https://pub.dev/packages/flare_dart) is no longer maintained as a separate package, it has now been rolled into [flare_flutter](https://pub.dev/packages/flare_flutter). Please use only [flare_flutter](https://pub.dev/packages/flare_flutter) going forward.

## Examples
Take a look at the provided [example applications](https://github.com/2d-inc/Flare-Flutter/tree/master/example).

Please note that only the [simple](example/simple), [change_color](example/change_color), and [teddy](example/teddy) have been updated to null safety.

## License
See the [LICENSE](LICENSE) file for license rights and limitations (MIT).
