# flutter_hello_world

A new Flutter project.

Made Together with My teacher

## Learning
- `void main()` is the main function
- We use `StatelessWidget`, it means this State will not change
- We use `MaterialApp` that had a content
- `home` is the first widget that will be shown
- We use `Scaffold`, it's kind like a media to put a whole widget in the screen
- We use `AppBar` to make a Top Bar
- We use `Text` to make text in Top Bar
- We use `body` to make an usable area bottom of appBar
- We use `Center` so the body will going center based in both vertical and horizontal
- We use `Text` again, we will use this widget all around our course :D

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.

```dart
// The Code

class MyApp extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(title: Text("Aplikasi Hello World"),),
        body: Center(child: Text("Hello World!")),
      ),
    );
  }
}

```