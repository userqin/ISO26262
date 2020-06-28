# Fault-related terms and definitions

## 3.54 Fault

abnormal condition that can cause an element \(3.41\) or an item \(3.84\) to fail.

Note 1 to entry: permanent, intermittent, and transient faults \(3.173\) \(especially soft errors\) are considered. 

Note 2 to entry: when a subsystem is in an error \(3.46\) state it could result in a fault for the system \(3.163\). 

Note 3 to entry: an intermittent fault occurs from time to time and then disappears again. This type of fault can occur when a component \(3.21\) is on the verge of breaking down or, for example, due to an internal malfunction in a switch. Some systematic faults \(3.165\) \(e.g., timing irregularities \) could lead to intermittent faults.

## 3.31 Detected fault

fault \(3.54\) whose presence is detected within a prescribed time by a safety mechanism \(3.14\)

在规定时间内可由安全机制探测到到故障

## 3.39 Dual-point fault （双点故障）

individual fault \(3.54\) that, in combination with another independent fault \(3.54\), leads to a dual-point failure \(3.38\)

与另一个独立故障组合而导致双点失效（3.38）的一个故障

Note 1 to entry:  a dual-point fault can only be recognized after the identification of a dual-point failure \(3.38\), e.g. from cut set analysis of a fault tree.

只有在明确双点失效后才能识别出一个双点故障，例如通过故障树的割集分析。

Note 2 to entry: see also multiple-point fault \(3.97\)

## 3.57 Fault injection

method to evaluate the effect of a fault \(3.54\) within an element \(3.41\) by inserting faults \(3.54\), errors\(3.46\), or failures \(3.50\) in order to observe the reaction by observation points \(3.101\)

Note 1 to entry:  fault injection can be performed at various levels of abstraction including item \(3.84\) or element \(3.41\) level depending on the scope, feasibility, observability and level of required detail. Depending on purpose, it can be performed at different stages of the safety lifecycle and by considering different fault models \(3.58\).

Example 1: injecting faults \(3.54\) during operation to verify that a safety mechanism \(3.142\) is working properly as part of a strategy to detect latent faults \(3.85\).

Example 2: injecting faults \(3.54\) during integration test through hardware debug ports or through dedicated software commands to test the hardware-software interface \(HSI\).

Example 3: simulating stuck-at faults \(3.54\) or transient faults at hardware component level to verify the diagnostic coverage \(3.33\) of a safety mechanism \(3.142\) or to identify faults \(3.54\) which may result in errors \(3.46\) or failures \(3.50\).

## 3.58 Fault model

representation of failure modes \(3.51\) resulting from faults \(3.54\).

Note 1 to entry: fault models are used to assess consequences of particular faults \(3.54\).

## 3.60 Fault tolerance

ability to deliver a specified functionality in the presence of one or more specified faults \(3.54\) 

Note 1 to entry: specified functionality can be intended functionality \(3.83\)

## 3.85 Latent fault

multiple-point fault \(3.97\) whose presence is not detected by a safety mechanism \(3.142\) nor perceived by the driver within multiple-point fault detection time interval \(3.98\).

## 3.97 Multiple-point fault

individual fault \(3.54\) that, in combination with other independent faults \(3.54\), if undetected and not perceived, could lead to a multiple-point failure \(3.96\).

Note 1 to entry:  a multiple-point fault can only be recognized after the identification of a multiple -point failure \(3.96\), e.g., from cut set analysis of a fault tree. 一个多点故障仅在识别出多点失效后才能被辨别出来，例如，通过故障树点割集分析。

## 3.108 Perceived fault

fault \(3.54\) that may be perceived indirectly \(through deviating behavior on vehicle level\)

## 3.109 Permanent fault

fault \(3.54\) that occurs and stays until removed or repaired.

Note 1 to entry: direct current \(d.c.\) faults \(3.54\) e.g., stuck-at, and bridging faults \(3.54\) are permanent faults.

## 3.119 Random hardware fault

hardware fault \(3.54\) with a probabilistic distribution

## 3.125 Residual fault

multiple-point fault \(3.97\) whose presence is not detected by a safety mechanism \(3.142\) nor perceived by the driver within the multiple-point fault detection time interval \(3.98\)

Note 1 to entry: this presumes that the hardware element \(3.41\) has safety mechanism \(3.142\) coverage for only a portion of its faults \(3.54\).

Example 1: if a set of faults \(3.54\) which is safety-relevant and not safe has a subset within 60% coverage, then the remaining 40% of the set faults \(3.54\) are residual faults.

## 3.130 Safe fault

fault \(3.54\) whose occurrence will not significantly increase the probability of violation of a safety goal \(3.139\)

Note 1 to entry: As shown in ISO 26262-5:2018, Annex B, both non-safety and safety-related elements \(3.144\) can have safe faults. 

Note 2 to entry: Single-point faults \(3.156\), residual faults \(3.125\) and dual-point faults \(3.39\) do not constitute safe faults. 

Note 3 to entry: Unless shown relevant in the safety \(3.132\) concept, multiple-point faults \(3.97\) with higher order than 2 can be considered as safe faults.

## References

1. [ISO 26262-3:2018 Road vehicles — Functional safety ](https://www.iso.org/standard/68383.html)

