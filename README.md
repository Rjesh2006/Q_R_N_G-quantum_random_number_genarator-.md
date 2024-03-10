# Random Number Generation Overview

## Introduction
Random numbers play a crucial role in various fields such as science, technology, and everyday life. They are sequences of numbers or symbols that cannot be predicted other than by random chance computed by any algorithm. 

### Characteristics of True Randomness
- Unpredictability
- Uniform distribution of the bits in the sequence
- Lack of patterns in the sequence

## Methods of Random Number Generation

### Pseudo-Random Number Generator (PRNG)
- PRNGs use mathematical algorithms to approximate the behavior of randomness.
- They produce long sequences of data determined by an initial state or seed.
- Issues: determinism due to the initial seed, periodicity, correlations, lack of uniformity.

### True Random Number Generator (TRNG)
- TRNGs extract randomness from physical processes that behave in a non-deterministic way.
- They rely on chaotic systems or unpredictable physical phenomena.
- Advantages: better candidates for true random number generation.

## Characteristics and Limitations
- PRNGs suffer from determinism, lack of true unpredictability, and other issues.
- TRNGs are better suited for generating truly random numbers but may have limitations like sensitivity to initial conditions and vulnerabilities to attacks.

## Conclusion
In summary, while both PRNGs and TRNGs have their uses, TRNGs are generally preferred for applications requiring higher levels of randomness and unpredictability. It's crucial to understand the trade-offs and vulnerabilities associated with each method when selecting a random number generation approach for specific applications.

