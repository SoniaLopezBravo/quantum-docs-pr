---
uid: Microsoft.Quantum.Canon.ApplyWithA
title: ApplyWithA operation
ms.date: 10/28/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: ApplyWithA
qsharp.summary: Given two operations, applies one as conjugated with the other.
---

# ApplyWithA operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Given two operations, applies one as conjugated with the other.

```qsharp
operation ApplyWithA<'T> (outerOperation : ('T => Unit is Adj), innerOperation : ('T => Unit is Adj), target : 'T) : Unit
```


## Description

Given two operations, respectively described by unitary operators $U$

## Input

### outerOperation : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

The operation $U$ that should be used to conjugate $V$. Note that the


### innerOperation : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

The operation $V$ being conjugated.


### target : 'T

The input to be provided to the outer and inner operations.



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Type Parameters

### 'T

The target on which each of the inner and outer operations act.

## Remarks

The outer operation is always assumed to be adjointable, but does not

## See Also

- [Microsoft.Quantum.Canon.ApplyWith](xref:Microsoft.Quantum.Canon.ApplyWith)
- [Microsoft.Quantum.Canon.ApplyWithC](xref:Microsoft.Quantum.Canon.ApplyWithC)
- [Microsoft.Quantum.Canon.ApplyWithCA](xref:Microsoft.Quantum.Canon.ApplyWithCA)