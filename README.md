# C\# Basics
### Notes by Xenon Santillan
----------------------------------------------------------------

### C\# vs .NET Framework

- C# is a programming language

- .NET is a framework for building applications on Windows

.NET consists of two components:

- Common Language Runtime (CLR): a component of the .NET Framework that manages the execution of .NET applications.

When a C\# program is compiled, the resulting executable code is in an intermediate language called Common Intermediate Language(CIL) or Microsoft Intermediate Language(MSIL).

- Class Library: a component of the .NET Framework that includes classes, interfaces, delegates, and value types that expedite and optimize the development process and provide access to system functionality.

[.NET class library documentation](https://learn.microsoft.com/en-us/dotnet/standard/class-library-overview)

----------------------------------------------------------------
### Architecture of .NET Applications

When creating a C\# application, it will be composed of several different classes. Classes contain multiple attributes and are responsible for program functionality. 

Namespace: a keyword that is used to declare a scope that contains a set of related objects. You can use a namespace to organize code elements and to create globally unique types.

Assembly: a collection of types and resources that are built to work together and form a logical unit of functionality. These can take the form of Dynamic link library (.dll) or Executables (.exe)

