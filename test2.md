Quiz 1
A. byte, short, int, long
B. float, double, char, boolean
C. String, Integer, Double, Boolean
D. class, interface, array, object
A. It has been declared but not assigned
B. It has been assigned a value
C. It has been converted into a class
D. It has gone out of scope
A. MyInt
B. my_int
C. myInt
D. MYINT
A. It becomes global
B. It becomes static
C. It is destroyed/unavailable
D. It is automatically saved
A. +
B. -
C. #
D. *

Quiz 2
A. implements
B. inherits
C. extends
D. super
A. Anywhere in the constructor
B. As the first call in the constructor
C. After all instance variables are assigned
D. Only inside an if statement
A. Java creates a duplicate key
B. The old value is overwritten
C. The program always crashes
D. The new value is ignored
A. Product
B. Book
C. Object
D. String
A. It must only contain abstract methods
B. It cannot have fields
C. It cannot be instantiated directly
D. It cannot be used as a variable type
B. equals()
C. compare()
D. match()
String text = "Java";
System.out.println(text.toUpperCase());
B. java
C. JAVA
D. Error
Integer x = 10;
ArrayList<String> colors = new ArrayList<>();
colors.add("Red");
colors.add("Blue");
colors.add(1, "Green");
System.out.println(colors.get(2));
Exception
IOException
IOException
FileNotFoundException
FileNotFoundException
IOException
Answer Key
B
C
A
B
C
B
C
C
C
D
Java Practice Quiz 2
"Hello".equals("hello");
String s = "Programming";
System.out.println(s.substring(3, 6));
try {
riskyMethod();
} catch (Exception e) {
System.out.println("Something went wrong.");
}
attempt {
riskyMethod();
} stop (Exception e) {
System.out.println("Something went wrong.");
}
catch (Exception e) {
System.out.println("Something went wrong.");
}
try {
riskyMethod();
}
int value = 5;
public void show(int value) {
System.out.println(this.value);
System.out.println(value);
}
show(8);
5
8
8
5
8
8
5
5
ArrayList<Integer> nums = new ArrayList<>();
nums.add(10);
nums.add(20);
nums.add(30);
System.out.println(nums.get(1));
assertEquals(getCount(), 42);
assertEquals(getCount(), 22);
assertTrue(getCount() == 22);
Based only on the variables/UML/JUnit notes in test1.md.

1. Which of the following are Java primitive integer types?

2. What does it mean when a variable is initialized?

3. Which variable name follows the standard Java variable naming convention described in the notes?

4. What happens to a local variable when the method block it is declared in ends?

5. In UML class diagrams, what symbol represents a private field or method?

Based only on the inheritance, HashMap, polymorphism, abstract class, static, wrapper, and related notes in test2.md.

1. Which keyword is used to create an inheritance relationship in Java?

2. In a subclass constructor, where must a call to super() appear?

3. What happens if you use put() with the same key twice in a HashMap?

4. In Product p = new Book();, what is the dynamic type?

5. What is true about an abstract class?

Java Practice Quiz 1

1. Which method correctly compares the contents of two String objects?

A. ==

2. What is printed?

A. Java

3. Which declaration creates an ArrayList of Integers?

A. ArrayList<Integer> list = new ArrayList<>();

B. ArrayList<int> list = new ArrayList<>();

C. List<Integer> = new ArrayList<>();

D. Array<Integer> list = new ArrayList<>();

4. What does JVM stand for?

A. Java Variable Method

B. Java Virtual Machine

C. Java Visual Manager

D. Java Version Manager

5. Which keyword is used to catch an exception?

A. throw

B. try

C. catch

D. finally

6. What is happening in the following code?

A. Automatic unboxing

B. Automatic boxing (autoboxing)

C. Casting

D. Inheritance

7. Which collection stores key-value pairs?

A. ArrayList

B. LinkedList

C. HashMap

D. HashSet

8. What is printed?

A. Red

B. Green

C. Blue

D. Error

9. Which exception should be caught first?

A.

B.

C.

D. It doesn't matter.

10. A public class named Student must be stored in which file?

A. student.java

B. Student.class

C. Main.java

D. Student.java

1. What is the result of the following operation?

A. true

B. false

C. Hello

D. Error

2. Which method replaces all literal occurrences of a substring?

A. replace()

B. replaceAll()

C. split()

D. substring()

3. What is printed?

A. rog

B. gra

C. ram

D. amm

4. Which declaration correctly creates a HashMap with String keys and Double values?

A. HashMap<String, Double> map = new HashMap<>();

B. HashMap<Double, String> map = new HashMap<>();

C. ArrayList<String, Double> map = new HashMap<>();

D. HashMap[String, Double] map = new HashMap<>();

5. Which code correctly handles an exception?

A.

B.

C.

D. Java has no exception handling.

6. What is printed?

A.

B.

C.

D.

7. What is printed?

A. 10

B. 20

C. 30

D. Error

8. What happens if you close System.in?

A. No more keyboard input can be read until the program restarts.

B. Input is redirected to System.out.

C. It automatically reopens.

D. Nothing happens.

9. Which of the following is one of the four pillars of Object-Oriented Programming?

A. Pancakes

B. Interface

C. Inheritance

D. ArrayList

10. Assume getCount() returns 42. Which assertion passes?

A.

B.

C.


D. None of the above.