This style guide outlines the coding conventions of [Alven
Diaz](http://www.zaidox.com) ([@zaidos](http://www.twitter.com/zaidos)).

## Introduction

This guide is a work in progress. Updates and changes should be expected.

## Credits

## Background

TODO: Add references to other .NET style guides here.

## Table of Contents

- [Language](#language)
- [Spacing](#spacing)
- [Line Breaks](#line-breaks)
- [Comments](#comments)
- [Documentation](#documentation)
- [Naming](#naming)
- [Namespaces](#namespaces)
- [Using Statements](#using-statements)
- [Code Organization](#code-organization)
- [Object Declaration](#object-declaration)
- [Primitive Types](#primitive-types)
- [Methods](#methods)
- [Variables](#variables)
- [Properties](#properties)
- [Constants](#constants)
- [Enumerated Types](#enumerated-types)
- [Case Statements](#case-statements)
- [Private Properties](#private-properties)
- [Booleans](#booleans)
- [Conditionals](#conditionals)
 - [Ternary Operator](#ternary-operator)
 - [Null Coalescing Operator](#null-coalescing-operator)
- [Reference Types](#reference-types)
- [Try Methods](#try-methods)
- [Anonymous Types](#anonymous-types)
- [Dynamic Types](#dynamic-types)
- [Interfaces](#interfaces)
- [Constructors](#constructors)
- [Deconstructors](#deconstructors)
- [IDisposable](#idisposable)
- [Lambdas](#lambdas)
- [LINQ](#linq)
  - [Method Chains](#method-chains)
- [Intended Path](#intended-path)
- [Error Handling](#error-handling)
- [Singletons](#singletons)
- [Visual Studio Project Organization](#project-organization)

## Language

Ideally, US English should be used.

**Preferred:**
```csharp
var flavor = Flavor.MintChocolateChip;
```

**Not Preferred:**
```csharp
var flavour = Flavor.StrawberryWithChunks;
```

## Spacing

- Line indentation should be set to two spaces. Due to the nature of .NET
  development shops, certain variable and class names can become rather lengthy.
  Any other size will cause too much horizontal scrolling, even on larger
  monitors.
- Interface, Class, Method, Switch/Case, and conditionals braces should always
  open and close on a new line.

**Preferred:**
```csharp
public class Dog
{
  public void MakeNoise()
  {
    if (nightTime)
    {
      BarkReallyLoud();
    }
  }
}
```

**Not Preferred:**
```csharp
public class Cat {
  public void MakeNoise() {
    if (nightTime) {
      AwakeOwner();
    }
  }
}
```

## Line Breaks



## Comments

Ideally, code should be as self-documenting as possible. Comments should never
explain what a particular piece of code does.

If a comment is needed, it should explain **WHY** the code was written that way,
and only when its meaning is not inherently clear.

## Future Reading

## References
