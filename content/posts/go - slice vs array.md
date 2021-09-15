---
title: "Go - Arrays and Slices"
author: "Gagandeep Singh"
author: "Gagandeep Singh"
date: "2021-09-10"
categories: 
  - "go"
tags: 
  - "go"
  - "golang"
draft: false
---

### Arrays

Like any other programming language, _arrays_ in Go are used to group elements of **fixed length** together. Arrays can only hold elements of same type. Whenever an array is declared or initialized the type of array has to be defined. Type of elements and the length are both used to defined the type of the array. For example, the array below can store string values and it's length is 4, so its type is **[4]string**.

```go
var names [4]string
```

The default values of an array are the Zero values, which is based on the data type of array. In the above array since the data type is string, so the defult Zero values in this case will be "" (empty string).

Values can be set like this:

```go
  name[0]="Eeny"
  name[1]="Meeny"
  name[2]="Miny"
  name[3]="Moe"
```

There is another way to define and initiaize array in a single statement.

```go
  name := [4]string{"Eeny", "Meeny", "Miny", "Moe"}
```

*Once the length of array has been defined, it cannot be changed*. An array of size 4 cannot have 5 or more elements.
