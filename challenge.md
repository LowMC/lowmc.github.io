---
layout: default
---

## The LowMC cryptanalysis challenge

The LowMC cryptanalysis challenge is a set of attack challenges on different
LowMC block cipher instances. It offers an opportunity to cryptanalyze
block ciphers differing from most traditional designs allowing you to 
apply techniques that might not be competetive on other block ciphers.
Apart from eternal fame, you can also win **prizes**.

For each challenge, there are two attack targets. The first is to find
the most time efficient attack on a round-reduced version of the LowMC
instance. The second challenge is to break a number of rounds deemed secure
by the designers.

If you win a prize, you can choose a present from one of the countries of
people involved in the design of LowMC: Austria, Denmark, Germany, Iran, and
the United Kingdom.

**Deadline:** November 1st, 2017.

### Challenges
The attack challenges cover three types of LowMC instantiations that
are optimized with respect to different metrics: 
 * Challenge I: Minimizing total multiplications,
 * Challenge II: Minimizing the multiplicative depth,
 * Challenge III: Minimizing multiplications per encrypted bit.

#### Challenge I

| Block size | Key size | S-boxes per round | data complexity |
|:-----------|:---------|:------------------|:----------------|
| 256        | 256      | 1                 | 1               |

**Fast attack goal:** 243 rounds
**Cutting edge attack goal:** 380 rounds

#### Challenge II

| Block size | Key size | S-boxes per round | data complexity |
|:-----------|:---------|:------------------|:----------------|
| 256        | 128      | 85                | 1               |

**Fast attack goal:** 5 rounds
**Cutting edge attack goal:** 8 rounds

| Block size | Key size | S-boxes per round | data complexity |
|:-----------|:---------|:------------------|:----------------|
| 256        | 128      | 85                | 128               |

**Fast attack goal:** 11 rounds
**Cutting edge attack goal:** 14 rounds

#### Challenge III

| Block size | Key size | S-boxes per round | data complexity |
|:-----------|:---------|:------------------|:----------------|
| 1024       | 128      | 1                 | 128             |

**Fast attack goal:** 600 rounds
**Cutting edge attack goal:** 901 rounds

### Contact
If you have any questions, or want to submit an attack write to:
``` tyti (ett) dtu (dot) dk ```

[Go back](./)
