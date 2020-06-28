# Failure-related terms and definitions

## 3.50 Failure

termination of an intended behavior of an element \(3.41\) or an item \(3.84\) due to a fault \(3.54\)

由于故障所导致的要素的或者元件的预期行为的终止

## 3.51 Failure mode

manner in which an element or an item fails to provide the intended behavior

## 3.52 Failure mode coverage \(FMC\)

proportion of the failure rate \(3.53\) of a failure mode \(3.51\) of a hardware element \(3.41\) that is detected or controlled by the implemented safety mechanism \(3.142\)

## 3.53 Failure rate

probability density of failure \(3.50\) divided by probability of survival for a hardware element \(3.41\)

Note 1 to entry: the failure rate is assumed to be constant is generally denoted as λ.

## Base failure rate \(BFR\)

failure rate \(3.53\) of a hardware element \(3.41\) in a given application use case used as an input to safety \(3.132\) analyses 

给定应用程序用例中的硬件元素（3.41）的故障率（3.53\), 用作安全性（3.132）分析的输入

## Single-point failure

## Dual-point failure

## Multiple-point failure

failure \(3.50\) resulting from the combination of several independent hardware faults \(3.54\), which leads directly to the violation of a safety goal \(3.139\).

## Cascading failure \(级联失效\)

failure \(3.50\) of an element \(3.41\) of an item \(3.84\) resulting from a root cause \[ inside or outside of the element \(3.41\) \] and then causing a failure \(3.50\) of another element \(3.41\) or elements \(3.41\) of the same or different item \(3.84\)

由根本原因 \[ 要素（3.41）的内部或外部 \] 导致项目（3.84）的要素（3.41）的失效（3.50）然后导致相同或不同项目（3.84）的一个要素（3.41）或多个要素（3.41）的失效（3.50）

> Note 1 to entry: cascading failures are dependent failures \(3.29\) that could be one of the possible root causes of a common failure \(3.18\). See Figure 2.

> 注: 级联失效是一个共因失效的某个根本原因引起的相关失效 \(3.29\) 见图2

![](../.gitbook/assets/wechatimg402.png)

Figure 2 indicates that：

* an external root cause caused a Fault 1 in Element A which led to a Failure A. Then this Failure A caused Fault 2 in Element B which led to a Failure B;
* an internal root cause caused a Fault 1 in Element A which led to a Failure A. Then this Failure A caused a Fault 2 in Element B which led to a Failure B

## Common Cause Failure \(CCF\)

## 3.79 Independent Failures

failures \(3.50\) whose probability of simultaneous or successive occurrence can be expressed as the simple product of their unconditional probabilities.

> Note 1 to entry: independent failures can include software failures \(3.50\) even if their probability of failure is not calculated.



## References

1. [ISO 26262-3:2018 Road vehicles — Functional safety ](https://www.iso.org/standard/68383.html)

