## [📁 Notion Page Link](https://www.notion.so/Daily-Math-Problem-DAY-1-2a76760c955380c69e50c30eb2691973?source=copy_link)

Translated to bahasa Indonesia: [Indonesia](https://www.notion.so/Daily-Math-HARI-1-2a86760c9553807f85ffebf00274f440?source=copy_link)

---

# Daily Math Problem - DAY 1

### Problem Metadata
- **Date**: 2025-11-11
- **Problem Number**: #1
- **Topic**: Vector Equality in ℝⁿ
- **Category**: Machine Learning Math / Linear Algebra
- **Difficulty Level**: Beginner
- **Problem Curator**: Phanie

### Problem Statement

**(a)** Identify the dimensions of the following vectors:
- (2, −5)
- (7, 9)
- (0, 0, 0)
- (3, 4, 5)

The first two vectors belong to R², whereas the last two belong to R³.  

The third is the zero vector in R³.

**(b)** Find x, y, z such that (x − y, x + y, z − 1) = (4, 2, 3)  

By definition of equality of vectors, corresponding entries must be equal. Thus,

```
x - y = 4, x + y = 2, z - 1 = 3
```

### Source and Attribution
- **Primary Source**: Schaum's Outline of Linear Algebra, Fourth Edition (Schaum's Outline Series) by Seymour Lipschutz, Marc Lipson
- **Related Materials**: Linear Algebra Done Right by Sheldon Axler

### Motivation and Context

**Why This Matters:**
Vectors in ℝⁿ formalize "ordered lists of numbers." Equality is entrywise; operations are addition and scalar multiplication. This problem checks recognition of vector dimension and uses equality to turn one vector equation into a small linear system.

**Relevance to ML/DL/AI:**
- Data samples/features are vectors in ℝⁿ
- Zero vector, dimensionality, and componentwise equality underpin batching, broadcasting, and shape checks in NumPy/PyTorch
- Solving for (x, y, z) from a vector equation uses the same algebra as parameter fitting with linear constraints

**Theoretical Significance:**
- Definitions: ℝⁿ, zero vector, vector equality
- Operations: vector addition, scalar multiplication (parallelogram rule)
- Translating a vector identity to a system of linear equations

**Key Terms:**
- *Entrywise*: operations or comparisons performed on corresponding entries (elements) of vectors or matrices, one entry at a time
- *Componentwise*: also called entrywise or element-wise

### Hints and Guidance

**Consider:**
- **Equality of vectors**: (a₁, ..., aₙ) = (b₁, ..., bₙ) ⇔ aᵢ = bᵢ for all i
- **Dimensionality**: a 2-tuple is in ℝ²; a 3-tuple is in ℝ³; (0, …, 0) is the zero vector
- **Approach**: From (x − y, x + y, z − 1) = (4, 2, 3), write the three scalar equations and solve the 2×2 system for x, y, then get z

### Discussion Space

**Questions:**
- Any confusion about why vectors with the same multiset of numbers (e.g., (1, 2, 3) vs (2, 3, 1)) are not equal?
- Do you see how dimension mismatches (e.g., comparing a pair to a triple) invalidate equality?

**Initial Observations:**
- From equality: x − y = 4, x + y = 2
- From the third component: z − 1 = 3
- The first two listed vectors are in ℝ²; the latter two are in ℝ³; (0, 0, 0) is the zero vector

### Status Tracking
- **In Progress**: TBA

### Solutions Available
| Participant | Solution Link | Date Submitted | Notes |
|-------------|---------------|----------------|-------|
| Phanie's Mom | [View](https://github.com/lymphoidcell/daily-math/blob/main/Solutions/Phanie's%20Mom/Phanie's%20Mom%20-%20DAY%201.png) | 11 November 2025 | Using eliminations followed by substitution method |
| Phanie | [View](https://github.com/lymphoidcell/daily-math/blob/main/Solutions/Phanie/DAY%201%20-%20Daily%20Math%20Solution.pdf) | 11 November 2025 | [Chapter 1: Introduction to Vectors in Rⁿ and Cⁿ](https://www.notion.so/Chapter-1-Introduction-to-Vectors-in-R-and-C-2a86760c95538066a713da73ee81394f?source=copy_link) |

### External Resources
| Source | Topic | Brief Description |
|--------|-------|-------------------|
| [1. The Geometry of Linear Equations](https://www.youtube.com/watch?v=J7DzL2_Na80&t=430s) | Addresses the fundamental problem of solving a system of linear equations (Ax=b) | The geometric implications of solutions, including the "big picture" question of whether solutions exist for every right-hand side vector, which depends on whether the column combinations fill the space, leading to discussions of non-singular (invertible) and singular matrices. |
| [Solving Systems of Equations By Elimination & Substitution With 2 Variables](https://www.youtube.com/watch?v=oKqtgz2eo-Y) | Elimination and substitution | This algebra video tutorial explains how to solve systems of equations by elimination and how to solve systems of equations by substitution with 2 variables. |
| [A Guide to Gaussian Elimination Method](https://www.youtube.com/watch?v=seet9VyHo3Q) | Gaussian elimination | A step by step algorithm for performing the Gaussian elimination method on a matrix. |

