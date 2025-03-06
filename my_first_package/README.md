# SayHello

SayHello is a simple Flutter package that provides a method to return a greeting message.

## Installation

Add the following dependency to your `pubspec.yaml` file:

```yaml
dependencies:
  say_hello:
    git:
      url: https://github.com/dilrabo-vic24/my_packages.git
```

Then run:

```sh
flutter pub get
```

## Usage

Import the package:

```dart
import 'package:my_first_package.dart';
```

Create an instance of `SayHello` and use the `sayHello` method:

```dart
void main() {
  SayHello greeting = SayHello();
  print(greeting.sayHello(name: "John")); // Output: Hello John
}
```

## Features
- Simple and lightweight
- Requires only a name parameter

## Contributions
Contributions are welcome! Feel free to submit issues and pull requests.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

