# Dart

### Creating a Custom Digit

```dart
class WidgetName extends StatelessWidget {
	final String variable;

	// constructor
	WidgetName(this.variable);

	@override
	Widget build(BuildContext context) {
		return Text();
	}
}
```

### Example of Map

```dart
final questions = [
	{
		'questionText': 'What is your favorite color?',
		'answers': ['Black', 'Orange', 'Yellow']
	},
	{
		'questionText': 'What is your favorite animal?',
		'answers': ['Cat', 'Dog', 'Bird']
	}

	// to access map
	questions[0]['questionText'] // = What is your favorite color?
	questions.map();
];
```
