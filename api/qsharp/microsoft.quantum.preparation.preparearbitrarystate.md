---
uid: Microsoft.Quantum.Preparation.PrepareArbitraryState
title: PrepareArbitraryState operation
ms.date: 10/28/2020 12:00:00 AM
ms.topic: article
qsharp.kind: operation
qsharp.namespace: Microsoft.Quantum.Preparation
qsharp.name: PrepareArbitraryState
qsharp.summary: >-
  Given a set of coefficients and a little-endian encoded quantum register,
  prepares an state on that register described by the given coefficients.
---

# PrepareArbitraryState operation

Namespace: [Microsoft.Quantum.Preparation](xref:Microsoft.Quantum.Preparation)

Package: [](https://nuget.org/packages/)


Given a set of coefficients and a little-endian encoded quantum register,

```qsharp
operation PrepareArbitraryState (coefficients : Microsoft.Quantum.Math.ComplexPolar[], qubits : Microsoft.Quantum.Arithmetic.LittleEndian) : Unit
```


## Description

This operation prepares an arbitrary quantum

## Input

### coefficients : [ComplexPolar](xref:Microsoft.Quantum.Math.ComplexPolar)[]

Array of up to $2^n$ complex coefficients represented by their


### qubits : [LittleEndian](xref:Microsoft.Quantum.Arithmetic.LittleEndian)

Qubit register encoding number states in little-endian format. This is



## Output : [Unit](xref:microsoft.quantum.lang-ref.unit)



## Remarks

Negative input coefficients $r_j < 0$ will be treated as though

## References

- Synthesis of Quantum Logic Circuits

## See Also

- [Microsoft.Quantum.Preparation.ApproximatelyPrepareArbitraryState](xref:Microsoft.Quantum.Preparation.ApproximatelyPrepareArbitraryState)