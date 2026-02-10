import 'package:flutter/material.dart';

void main() {
  runApp(const MyApp());
}

class MyApp extends StatelessWidget {
  const MyApp({super.key});

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      debugShowCheckedModeBanner: false,
      title: 'Student Info',
      theme: ThemeData(
        primarySwatch: Colors.blue,
      ),
      home: const StudentPage(),
    );
  }
}

class StudentPage extends StatelessWidget {
  const StudentPage({super.key});

  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(
        title: const Text("Student Information"),
        centerTitle: true,
      ),

      body: const Center(
        child: Card(
          elevation: 8,
          margin: EdgeInsets.all(20),
          child: Padding(
            padding: EdgeInsets.all(20),

            child: Column(
              mainAxisSize: MainAxisSize.min,
              crossAxisAlignment: CrossAxisAlignment.start,

              children: [

                /// الاسم
                Text(
                  " Ryan Al-Mutairi",
                  style: TextStyle(
                    fontSize: 20,
                    fontWeight: FontWeight.bold,
                  ),
                ),

                SizedBox(height: 15),

                /// الرقم التدريبي
                Text(
                  " 444328715",
                  style: TextStyle(
                    fontSize: 18,
                  ),
                ),

              ],
            ),
          ),
        ),
      ),
    );
  }
}
