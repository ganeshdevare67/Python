<h1>Python OOPs Concepts</h1>

<i>
<p>In Python, object-oriented Programming (OOPs) is a programming paradigm that uses objects and classes in programming. It aims to implement real-world entities like inheritance, polymorphisms, encapsulation, etc. in the programming. The main concept of OOPs is to bind the data and the functions that work on that together as a single unit so that no other part of the code can access this data. 
</i></p>
<!-- </h6> -->

<h3 style=color:blue>Main Concepts of Object-Oriented Programming (OOPs)</h3>

* Class

* Objects

* Inheritance

* Polymorphism

* Encapsulation

<h1>Class</h1> 

<p>A class is a collection of objects. A class contains the blueprints or the prototype from which the objects are being created. It is a logical entity that contains some attributes and methods. 
<p>
To understand the need for creating a class let’s consider an example, let’s say you wanted to track the number of dogs that may have different attributes like breed, age. If a list is used, the first element could be the dog’s breed while the second element could represent its age. Let’s suppose there are 100 different dogs, then how would you know which element is supposed to be which? What if you wanted to add other properties to these dogs? This lacks organization and it’s the exact need for classes. 

**Some points on Python class:**  

* Classes are created by keyword class.

* Attributes are the variables that belong to a class.

* Attributes are always public and can be accessed using the dot (.) operator. Eg.: Myclass.Myattribute

    
<h3>Class Definition Syntax:</h3>

![Screenshot (657)](https://user-images.githubusercontent.com/84759339/136652301-6dc82a0f-2072-494a-beab-4e7cbeb42e38.png)



<h1>Objects</h1>

The object is an entity that has a state and behavior associated with it. It may be any real-world object like a mouse, keyboard, chair, table, pen, etc. Integers, strings, floating-point numbers, even arrays, and dictionaries, are all objects. More specifically, any single integer or any single string is an object. The number 12 is an object, the string “Hello, world” is an object, a list is an object that can hold other objects, and so on. You’ve been using objects all along and may not even realize it.

**An object consists of:**

* State: It is represented by the attributes of an object. It also reflects the properties of an object.
* Behavior: It is represented by the methods of an object. It also reflects the response of an object to other objects.
* Identity: It gives a unique name to an object and enables one object to interact with other objects.

To understand the state, behavior, and identity let us take the example of the class dog (explained above). 

* The identity can be considered as the name of the dog.
* State or Attributes can be considered as the breed, age, or color of the dog.
* The behavior can be considered as to whether the dog is eating or sleeping.

![Screenshot (659)](https://user-images.githubusercontent.com/84759339/136652374-d95131dc-b751-4f69-b4c5-636c42f54ff0.png)


<h1>Inheritance</h1>

<p>Inheritance is the capability of one class to derive or inherit the properties from another class. The class that derives properties is called the derived class or base class and the class from which the properties are being derived is called the base class or parent class. The benefits of inheritance are:

* It represents real-world relationships well.
* It provides the reusability of a code. We don’t have to write the same code again and again. Also, it allows us to add more features to a class without modifying it.
* It is transitive in nature, which means that if class B inherits from another class A, then all the subclasses of B would automatically inherit from class A.

    
**Example: Inheritance in Python**
  
 ![Screenshot (661)](https://user-images.githubusercontent.com/84759339/136652419-9a730192-e0d2-4fa2-b480-f4ba26b8141c.png)

  <h1>Polymorphism</h1>
<p>
Polymorphism simply means having many forms. For example, we need to determine if the given species of birds fly or not, using polymorphism we can do this using a single function.

**Example: Polymorphism in Python**
  
  ![Screenshot (663)](https://user-images.githubusercontent.com/84759339/136652486-c6f0ca03-e103-48cd-824f-4dcb06baa788.png)

<h1>Encapsulation</h1>
<p>Encapsulation is one of the fundamental concepts in object-oriented programming (OOP). It describes the idea of wrapping data and the methods that work on data within one unit. This puts restrictions on accessing variables and methods directly and can prevent the accidental modification of data. To prevent accidental change, an object’s variable can only be changed by an object’s method. Those types of variables are known as private variables.

A class is an example of encapsulation as it encapsulates all the data that is member functions, variables, etc.
  
  ![Screenshot (665)](https://user-images.githubusercontent.com/84759339/136652526-00ddeecd-5e61-4962-9a70-c7a1e6484297.png)
  
 <h3 style=align:right>Learn all concept with the help of <i>GeeksforGeeks</i></h3>

  
