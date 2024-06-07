import 'package:flutter/material.dart';

void main() => runApp(MyApp());

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('집간다'),
        ),
        body: Center(
          child: Column(
            children: <Widget>[
              Text('5분남음'),
              Text('4분남음')
            ],
          ),
        ),
      ),
    );
  }
}
