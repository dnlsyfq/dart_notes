### Run File

```
dart file.dart
```

### Print

```
main(){
    print(var)
}
```

### Datatype

* int variable
* double variable
* var varialbe
* String var = 'str'
* bool variable = true|false
* var list = []
* var student = {'key':'value'}

```
int i,j,k // multiple declaring

int count; // null

final variable = '' // cant change values
final String variable = '' 
const variable = 1000;
var f = const [] // cant change
```

```
void main(){
  var name="Peter";
  var roll_no=24;
  print("My name is ${name}, My roll number is ${roll_no}");
}
```

### Dart Installation

```
https://dart.dev/get-dart
dart --version
```

```
dart _.dart
dart run __.dart
```

### Setting Project

```
dart create <name>
dart create --template console-full <name>

cd <name>
dart run bin/_.dart
dart _.dart
```

### Math Functions
cos(int)
sqrt(int)
max(int,int)


```
import 'dart:math';

void main(){
  print(sin(45 * pi/180));
}
```

### Variables

```
int number = 10;
number = 15;

double apple = 3.14;

10.isEven // true
3.14.round() 

num myNumber;
myNumber = 10;
myNumber = 3.14;
myNumber = 'ten' // wont work

dynamic myVariable;
myVariable = 10;
myVariable = 3.14;
myVariable = 'ten;
```

### Type inference
```
var someNumber = 10;
someNumber = 15l
someNumber = 3.14 // wont work

const myConstant = 10;

final hoursSinceMidnight = DateTime.now().hour;


```