# Dart basics

#### MInimal example
```dart
void main() {
  for (int i = 0; i < 5; i++) {
    print('hello ${i+1}');
  }

  int add(int a, int b) {
    return a + b;
  }
```

#### Dynamic types
```dart
dynamic a = 1;
dynamic b = 2;
dynamic c = a + b;
```

#### One-line functions
```dart
int function() => result;
```

#### List
```dart
List names = ['alex', 'bob'];
names.add('cyril');
```

#### Classes
```dart
class Animal {
  
}

class Dog extends Animal {
  Dog(int age) {
    this.age = age;
  }
  
  int age;
}

class SuperDog extends Dog {
  SuperDog(int age): super(int)
}

Dog d = Dog(5);
```

