---
uid: Microsoft.Quantum.Arrays.IsPermutation
title: IsPermutation function
ms.date: 10/28/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.Arrays
qsharp.name: IsPermutation
qsharp.summary: Outputs true if and only if a given array represents a permutation.
---

# IsPermutation function

Namespace: [Microsoft.Quantum.Arrays](xref:Microsoft.Quantum.Arrays)

Package: [](https://nuget.org/packages/)


Outputs true if and only if a given array represents a permutation.

```qsharp
function IsPermutation (permuation : Int[]) : Bool
```


## Description

Given an array `array` of length `n`, returns true if and only if

## Input

### permuation : [Int](xref:microsoft.quantum.lang-ref.int)[]

An array that may or may not represent a permutation.



## Output : [Bool](xref:microsoft.quantum.lang-ref.bool)



## Remarks

An array of length zero is trivially a permutation.