# C

### Primative Types

```csharp
string name = "Patrick";
char grade = 'A';
int age = 23;
double gpa = 3.83;
bool isMale = true;
```

### Loops

```csharp
while(x < 5)
{
	Console.WriteLine(x);
	x++;
}

do	// runs at least once
{
	Console.WriteLine();
	x++;
} while(x < 5);
```

```csharp
foreach (int element in fibNumbers)
{
    count++;
    Console.WriteLine($"Element #{count}: {element}");
}
```

### Strings

```csharp
string name = "Patrick";
name[2];							// t
name.ToLower();				// patrick
name.Contains("Pat");	// true
name.IndexOf("rick");	// 3
name.Substring(startIndex, optional:length);
```

### Arrays

```csharp
int[] primeNumbers = { 3, 5, 7, 11, 13, 17 };
string[] friends = new string[5];
friends[0] = "Kris";
friends[1] = "Brad";

int[,] numberGrid = {
	{1, 2},
	{3, 4},
	{5, 6}
};
int[,] myArray = new int [2,3];

Console.WriteLine(numberGrid[1, 1]);	// 4
```

### Methods

The name of the method should use PascalCase.

```csharp
static void HelloWorld()
{
	Console.WriteLine("Hello World!");
}
```

### Switch Statements

```csharp
string dayName;
switch(dayName)
{
	case 0:
		dayName = "Sunday";
		break;
	case 1:
		dayName = "Monday";
		break;
	// ...
	default:
		dayName = "Invalid day";
		break;
}
```

### Exception Handling

```csharp
try
{
	// Code
}
catch (Exception e)
{
	Console.WriteLine(e.Message);
}
```

### Basic Class

```csharp
// Book CLass
Class Book
{
	private string title;
	private string author;
	private int pages;

	public Book(string title, string author, int pages)
	{
		this.title = title;
		this.author = author;
		this.pages = pages;
	}
}

// Initialization Code
Book book1 = new Book("Lord of the Rings", "J.R.R. Tolkein", 900);
```

### Getters and Setters

### ArrayList

```csharp
ArrayList myAList = new ArrayList();
List<int> myList = new List<int>();
myList.Add(13);
```

### HashTable

```csharp
Hashtable hTable = new Hashtable();
htable.add(100, "Patrick");
htable.add(101, "Thompson");

hTable.ContainsKey(100);	// True
hTable.ContainsValue("Patrick");	// True

Console.WriteLine(hTable[100]);	// Patrick
```

Length of array
Length of string
