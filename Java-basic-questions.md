# Java 8 Interview Questions and Answers

## Q. What are the important features of Java 8 release?

* Interface methods by default;
* Lambda expressions;
* Functional interfaces;
* References to methods and constructors;
* Repeatable annotations
* Annotations on data types;
* Reflection for method parameters;
* Stream API for working with collections;
* Parallel sorting of arrays;
* New API for working with dates and times;
* New JavaScript Nashorn Engine ;
* Added several new classes for thread safe operation;
* Added a new API for `Calendar`and `Locale`;
* Added support for Unicode 6.2.0 ;
* Added a standard class for working with Base64 ;
* Added support for unsigned arithmetic;
* Improved constructor `java.lang.String(byte[], *)` and method performance `java.lang.String.getBytes()`;
* A new implementation `AccessController.doPrivileged` that allows you to set a subset of privileges without having to check all * other access levels;
* Password-based algorithms have become more robust;
* Added support for SSL / TLS Server Name Indication (NSI) in JSSE Server ;
* Improved keystore (KeyStore);
* Added SHA-224 algorithm;
* Removed JDBC Bridge - ODBC;
* PermGen is removed , the method for storing meta-data of classes is changed;
* Ability to create profiles for the Java SE platform, which include not the entire platform, but some part of it;
* Tools
    * Added utility `jjs` for using JavaScript Nashorn;
    * The command `java` can run JavaFX applications;
    * Added utility `jdeps` for analyzing .class files.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Can you declare an interface method static?

Java 8 interface changes include static methods and default methods in interfaces. Prior to Java 8, we could have only method declarations in the interfaces. But from Java 8, we can have default methods and static methods in the interfaces.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>

## Q. Why Java is not 100% Object-oriented?

Because of primitive data types namely: boolean, byte, char, int, float, double, long, short
we have wrapper classes which actually “wrap” the primitive data type into an object of that class.

<div align="right">
    <b><a href="#">↥ back to top</a></b>
</div>