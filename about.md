# Python 与 Java 基本语法对比速查表

---

## 1. 注释

### Python
```python
# 这是单行注释
"""
这是多行注释
"""
#python
x = 10
name = "Alice"
pi = 3.14

//java
int x = 10;
String name = "Alice";
double pi = 3.14;

#python
class Person:
    def __init__(self, name):
        self.name = name

    def greet(self):
        print("Hi, I'm " + self.name)

p = Person("Bob")
p.greet()

//java
public class Person {
    String name;

    Person(String name) {
        this.name = name;
    }

    void greet() {
        System.out.println("Hi, I'm " + name);
    }
}
// 在 main 方法中使用：
Person p = new Person("Bob");
p.greet();

```
---
# Finish



