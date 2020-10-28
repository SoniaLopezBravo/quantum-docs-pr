---
uid: Microsoft.Quantum.AmplitudeAmplification.FixedPointReflectionPhases
title: FixedPointReflectionPhases function
ms.date: 10/28/2020 12:00:00 AM
ms.topic: article
qsharp.kind: function
qsharp.namespace: Microsoft.Quantum.AmplitudeAmplification
qsharp.name: FixedPointReflectionPhases
qsharp.summary: >-
  Computes partial reflection phases for fixed-point amplitude
  amplification.
---

# FixedPointReflectionPhases function

Namespace: [Microsoft.Quantum.AmplitudeAmplification](xref:Microsoft.Quantum.AmplitudeAmplification)

Package: [](https://nuget.org/packages/)


Computes partial reflection phases for fixed-point amplitude

```qsharp
function FixedPointReflectionPhases (nQueries : Int, successMin : Double) : Microsoft.Quantum.AmplitudeAmplification.ReflectionPhases
```


## Input

### nQueries : [Int](xref:microsoft.quantum.lang-ref.int)

Number of queries to the state preparation oracle. Must be an odd


### successMin : [Double](xref:microsoft.quantum.lang-ref.double)

Target minimum success probability.



## Output : [ReflectionPhases](xref:Microsoft.Quantum.AmplitudeAmplification.ReflectionPhases)

Array of phases that can be used in fixed-point amplitude amplification

## References

We use the phases in "Fixed-Point Amplitude Amplification with