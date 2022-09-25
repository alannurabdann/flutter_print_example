# flutter_print_example

A new Flutter project using library : [Bluetooth Print](https://pub.dev/packages/bluetooth_print)

## WARNING!!!

Based on [this link](https://github.com/kakzaki/blue_thermal_printer/issues/70#issuecomment-813293797), please replace at line 22-27 with this codelab

``BluetoothPrint._() {
    _channel.setMethodCallHandler((MethodCall call) async{
      _methodStreamController.add(call);
    });
  }``

## Getting Started

This project is a starting point for a Flutter application.

A few resources to get you started if this is your first Flutter project:

- [Lab: Write your first Flutter app](https://flutter.dev/docs/get-started/codelab)
- [Cookbook: Useful Flutter samples](https://flutter.dev/docs/cookbook)

For help getting started with Flutter, view our
[online documentation](https://flutter.dev/docs), which offers tutorials,
samples, guidance on mobile development, and a full API reference.
