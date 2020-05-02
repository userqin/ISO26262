# Time related terms and definitions

### 3.35 Diagnostic test time interval \(DTTI\) <a id="3-35-Diagnostic-test-time-interval-DTTI"></a>

amount of time between the executions of online diagnostic tests by a safety mechanism \(3.142\) including duration of the execution of an online diagnostic test.

## 3.55 Fault detection time interval \(FDTI\)

time-span from the occurrence of a fault \(3.54\) to its detection

> Note 1 to entry : see Figure 5
>
> Note 2 to entry: Fault detection time interval is determined independently of diagnostic test time interval \(3.35\).
>
> EXAMPLE The fault detection time interval of a diagnostic test can be longer than the diagnostic test time interval \(3.35\) due to implemented error \(3.46\) counters, i.e. the fault \(3.54\) must be detected more than once by the diagnostic test before triggering an error \(3.46\) reaction.
>
> Note 3 to entry: Fault detection time interval, diagnostic test time interval \(3.35\), and fault reaction time interval \(3.59\) are relevant characteristics of a safety mechanism \(3.142\) based on fault \(3.54\) detection.
>
> Note 4 to entry: A fault \(3.54\) is timely covered by the corresponding safety mechanism \(3.142\) if the fault detection time interval plus the fault reaction time interval \(3.59\) is lower than the relevant fault tolerant time interval \(3.61\).

## 3.56 Fault handling time interval \(FHTI\)

## 3.98 Multiple-point fault detection time interval

time-span to detect a multiple-point fault \(3.97\) before it can contribute to a multiple-point failure \(3.96\)

## 3.108 Perceived fault

## 3.109 Permanent fault

## 3.119 Random hardware fault

## 3.125 Residual fault

## 3.130 Safe fault

fault \(3.54\) whose occurrence will not significantly increase the probability of violation of a safety goal \(3.139\)

> Note 1 to entry: As shown in ISO 26262-5:2018, Annex B, both non-safety and safety-related elements \(3.144\) can have safe faults.
>
> Note 2 to entry: Single-point faults \(3.156\), residual faults \(3.125\) and dual-point faults \(3.39\) do not constitute safe faults.
>
> Note 3 to entry: Unless shown relevant in the safety \(3.132\) concept, multiple-point faults \(3.97\) with higher order than 2 can be considered as safe faults.



