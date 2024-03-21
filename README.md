import 'package:flutter/material.dart';

void main() {
  runApp(jo());
}

class jo extends StatefulWidget {
  const jo({super.key});

  @override
  State<jo> createState() => _joState();
}

class _joState extends State<jo> {
  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        appBar: AppBar(
          title: Text('Naan kadavul'),
        ),
        body: SingleChildScrollView(
          child: Column(
            children: [
              Container(
                height: 200,
                color: Colors.red,
              ),
              Container(
                height: 300,
                color: Colors.black87,
              ),
              Container(
                height: 200,
                color: Colors.blue,
              ),
              Container(
                height: 200,
                color: Colors.deepOrange,
              ),
            ],
          ),
        ),
      ),
    );
  }
}
