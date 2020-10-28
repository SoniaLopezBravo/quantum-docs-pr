---
uid: Microsoft.Quantum.Canon.DelayA
title: DelayA operation
ms.date: 10/28/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Canon
qsharp.name: DelayA
qsharp.summary: Applies a given operation with a delay.
---

# DelayA operation

Namespace: [Microsoft.Quantum.Canon](xref:Microsoft.Quantum.Canon)

Package: [](https://nuget.org/packages/)


Applies a given operation with a delay.

```qsharp
operation DelayA<'T> (op : ('T => Unit is Adj), arg : 'T, aux : Unit) : Unit
```


## Description

Given an operation and an input to that operation, applies

## Input

### op : 'T => [Unit](xref:microsoft.quantum.lang-ref.unit) Adj

An operation to be applied.


### arg : 'T

The input to which the operation is applied.


### aux : [Unit](xref:microsoft.quantum.lang-ref.unit)

Argument used to delay the application of operation by using



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Type Parameters

### 'T

The input type of the operation to be delayed.

## See Also

- [Microsoft.Quantum.Canon.Delay](xref:Microsoft.Quantum.Canon.Delay)
- [Microsoft.Quantum.Canon.Delayed](xref:Microsoft.Quantum.Canon.Delayed)