---
layout: api
title: assertTrue
---
[stdlib](../index.html) / [kotlin.test](index.html) / [assertTrue](assertTrue.html)

# assertTrue
A number of helper methods for writing Kool unit tests
```
public fun assertTrue(message: String, block: ()->Boolean): Unit
```
Asserts that the given block returns true
```
public fun assertTrue(block: ()->Boolean): Unit
```
Asserts that the expression is true with an optional message
```
public fun assertTrue(actual: Boolean, message: String): Unit
```
## Description
```
public fun assertTrue(message: String, block: ()->Boolean): Unit
```
Asserts that the given block returns true
