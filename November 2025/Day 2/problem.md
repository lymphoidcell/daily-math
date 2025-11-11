## [📁 Notion Page Link](https://www.notion.so/Daily-Math-Problem-DAY-2-2a86760c955381d3b896c474926524f7)

Translated to bahasa Indonesia: [Indonesia](https://www.notion.so/Daily-Math-HARI-2-2a86760c9553819ea08bc52f703be28c)

---

# Daily Math Problem - DAY 2

### Problem Metadata
- **Date**: 2025-11-12
- **Problem Number**: #2
- **Topic**: Basic Vector Operations in ℝ³
- **Category**: Machine Learning Math / Linear Algebra
- **Difficulty Level**: Beginner
- **Problem Curator**: Phanie

### Problem Statement

**(a)** Vector addition and scalar multiplication

Let u = (2, 4, −5) and v = (1, −6, 9).

Then find:
- u + v
- 7u
- −v
- 3u − 5v

**(b)** The zero vector identity

The zero vector in ℝⁿ is 0 = (0, 0, ..., 0), similar to the scalar 0 in that, for any vector u = (a₁, a₂, ..., aₙ), show that:

```
u + 0 = u
```

**(c)** Linear combination of column vectors

[Perform the same operations as part (a) using column vector notation]

### Source and Attribution
- **Primary Source**: Schaum's Outline of Linear Algebra, Fourth Edition (Schaum's Outline Series) by Seymour Lipschutz, Marc Lipson
- **Related Materials**: Linear Algebra Done Right by Sheldon Axler

### Motivation and Context

**Why This Matters:**
This problem builds fluency with basic vector operations in ℝⁿ: addition, scalar multiplication, and the role of the zero vector. These are the foundational manipulations that everything else in linear algebra depends on.

**Relevance to ML/DL/AI:**
- Every data sample, weight vector, embedding, gradient, and parameter update in machine learning is expressed as a vector in ℝⁿ
- Training a model involves repeated operations of the form: w ← w − η∇L (a linear combination like w − ηg)
- Summing vectors in batches
- Scaling vectors when updating weights
- Being comfortable with linear combinations is necessary before understanding optimization, neural networks, and representation learning

**Theoretical Significance:**
This problem illustrates:
- Component-wise vector addition
- Scalar multiplication
- The identity property of the zero vector
- Linear combinations of vectors
- These operations are the building blocks of vector spaces and span/basis concepts later

**Key Terms:**
- *Linear combination*: an expression constructed from a set of vectors by multiplying each vector by a scalar and adding the results
- *Component-wise*: operations performed on corresponding components of vectors

### Hints and Guidance

**Consider:**
- **Vector addition** is done component by component: (a₁, a₂, ..., aₙ) + (b₁, b₂, ..., bₙ) = (a₁ + b₁, a₂ + b₂, ..., aₙ + bₙ)
- **Scalar multiplication** scales each component: k(a₁, a₂, ..., aₙ) = (ka₁, ka₂, ..., kaₙ)
- The **negative** of a vector is just scaling by −1
- For the zero vector property in part (b), use the identity: aᵢ + 0 = aᵢ for each component
- For part (c), treat column vectors the same way — operations are still componentwise

### Discussion Space

**Questions:**
- Do any components feel confusing when distributing the scalar?
- Does writing vectors in column form vs row form change the operations?

**Initial Observations:**
- In (a), each expression is a linear combination of u and v
- In (b), the proof is a direct componentwise identity check
- In (c), the structure is the same as (a), only written vertically

### Status Tracking
- **In Progress**: TBA

### Solutions Available
| Participant | Solution Link | Date Submitted | Notes |
|-------------|---------------|----------------|-------|
| Phanie's Mom | TBA | November 12, 2025 | TBA |
| Phanie | TBA | November 12, 2025 | [📓 Chapter 1 Introduction to Vectors in ℝⁿ and ℂⁿ](https://example.com) |
| TBA | TBA | TBA | TBA |

### External Resources
| Source | Topic | Brief Description |
|--------|-------|-------------------|
| TBA | TBA | TBA |
