# Probability Rules

This document provides simple definitions and examples of fundamental probability concepts: the Sum Rule, Product Rule, and Conditional Probability.

## 1. Sum Rule

### Definition
The Sum Rule states that the probability of the occurrence of at least one of several mutually exclusive events is equal to the sum of their individual probabilities.

### Formula
If \( A_1, A_2, ..., A_n \) are mutually exclusive events, then:
\[ P(A_1 \cup A_2 \cup ... \cup A_n) = P(A_1) + P(A_2) + ... + P(A_n) \]

### Example
Consider a die roll. Let:
- \( A_1 \): rolling a 1
- \( A_2 \): rolling a 2

Then:
\[ P(A_1) = \frac{1}{6}, \quad P(A_2) = \frac{1}{6} \]
\[ P(A_1 \cup A_2) = P(A_1) + P(A_2) = \frac{1}{6} + \frac{1}{6} = \frac{1}{3} \]

---

## 2. Product Rule

### Definition
The Product Rule states that the probability of the occurrence of two independent events is equal to the product of their individual probabilities.

### Formula
If \( A \) and \( B \) are independent events, then:
\[ P(A \cap B) = P(A) \cdot P(B) \]

### Example
Consider two coin flips. Let:
- \( A \): getting heads on the first flip
- \( B \): getting heads on the second flip

Then:
\[ P(A) = \frac{1}{2}, \quad P(B) = \frac{1}{2} \]
\[ P(A \cap B) = P(A) \cdot P(B) = \frac{1}{2} \cdot \frac{1}{2} = \frac{1}{4} \]

---

## 3. Conditional Probability

### Definition
Conditional Probability is the probability of an event occurring given that another event has already occurred.

### Formula
The conditional probability of event \( A \) given event \( B \) is given by:
\[ P(A | B) = \frac{P(A \cap B)}{P(B)} \]

### Example
Suppose we have a deck of cards. Let:
- \( A \): drawing an Ace
- \( B \): drawing a red card

Then:
\[ P(A) = \frac{4}{52}, \quad P(B) = \frac{26}{52} \]
\[ P(A \cap B) = \frac{2}{52} \] (2 red Aces)
\[ P(A | B) = \frac{P(A \cap B)}{P(B)} = \frac{\frac{2}{52}}{\frac{26}{52}} = \frac{2}{26} = \frac{1}{13} \]

---

## Conclusion

This document covers the basics of probability with definitions and examples for each concept. You can use these rules to better understand how probabilities are calculated in various scenarios.
