# Probability Rules

This document provides simple definitions and examples of fundamental probability concepts: the Sum Rule, Product Rule, and Conditional Probability.

## 1. Sum Rule

### Definition
The Sum Rule states that the probability of the occurrence of at least one of several mutually exclusive events is equal to the sum of their individual probabilities.

### Formula
If \( A_1, A_2, ..., A_n \) are mutually exclusive events, then:
\[ P(A_1 \cup A_2 \cup ... \cup A_n) = P(A_1) + P(A_2) + ... + P(A_n) \]

### Example
Consider the scenario of selecting a fruit from a basket containing an apple and a banana. Let:
- \( A_1 \): selecting an apple
- \( A_2 \): selecting a banana

Then:
\[ P(A_1) = \frac{1}{2}, \quad P(A_2) = \frac{1}{2} \]
\[ P(A_1 \cup A_2) = P(A_1) + P(A_2) = \frac{1}{2} + \frac{1}{2} = 1 \]

---

## 2. Product Rule

### Definition
The Product Rule states that the probability of the occurrence of two independent events is equal to the product of their individual probabilities.

### Formula
If \( A \) and \( B \) are independent events, then:
\[ P(A \cap B) = P(A) \cdot P(B) \]

### Example
Consider tossing a fair coin and rolling a fair die. Let:
- \( A \): getting heads on the coin toss
- \( B \): rolling a 3 on the die

Then:
\[ P(A) = \frac{1}{2}, \quad P(B) = \frac{1}{6} \]
\[ P(A \cap B) = P(A) \cdot P(B) = \frac{1}{2} \cdot \frac{1}{6} = \frac{1}{12} \]

---

## 3. Conditional Probability

### Definition
Conditional Probability is the probability of an event occurring given that another event has already occurred.

### Formula
The conditional probability of event \( A \) given event \( B \) is given by:
\[ P(A | B) = \frac{P(A \cap B)}{P(B)} \]

### Example
Suppose we have a bag with 3 red balls and 2 blue balls. Let:
- \( A \): drawing a red ball
- \( B \): drawing a ball that is not blue (either red or yellow)

Then:
\[ P(A) = \frac{3}{5}, \quad P(B) = 1 \] (since all balls are either red or blue)
\[ P(A \cap B) = P(A) = \frac{3}{5} \] (since drawing a red ball satisfies drawing a non-blue ball)
\[ P(A | B) = \frac{P(A \cap B)}{P(B)} = \frac{\frac{3}{5}}{1} = \frac{3}{5} \]

---

## Conclusion

This document covers the basics of probability with definitions and simpler examples for each concept. You can use these rules to better understand how probabilities are calculated in various scenarios.
