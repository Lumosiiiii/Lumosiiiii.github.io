# Python 与 Java 简单示例

## Python 代码

```python
x = 10
name = "Alice"
pi = 3.14

class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print("Hi, I'm " + self.name)

p = Person("Bob")
p.greet()
```

## Java 代码

```java
public class Person {
    String name;

    Person(String name) {
        this.name = name;
    }

    void greet() {
        System.out.println("Hi, I'm " + name);
    }
}

Person p = new Person("Bob");
p.greet();
```
