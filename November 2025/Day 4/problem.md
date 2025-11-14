## [📁 Notion Page Link](https://www.notion.so/Daily-Math-Problem-DAY-4-2aa6760c9553811b8b86f9d64eca9073?source=copy_link)

---

# Daily Math Problem - DAY 4

### Problem Metadata
- **Date**: 2025-11-14
- **Problem Number**: #4
- **Topic**: Dot Product, Orthogonality, Distance, Angle, Projection in ℝ³/ℝ⁴
- **Category**: Machine Learning Math / Linear Algebra
- **Difficulty Level**: Beginner
- **Problem Curator**: Phanie

### Problem Statement

We will work with vectors in Euclidean space. Answer all parts.

**(a) Dot Product Computation**

Let u = (2, −1, 4), v = (−3, 5, 2), and w = (1, 0, −6).

Compute:
- u · v
- u · w
- v · w

**(b) Dot Product Using Column Vectors**

Let u and v be column vectors.

Compute u · v.

**(c) Solve for k so the Vectors Are Orthogonal**

Let u = (3, 1, −2, 5) and v = (k, −4, 7, 1).

Find the value of k such that u and v are orthogonal.

**(d) Distance and Angle Between Two Vectors**

Let u = (4, −3, 1) and v = (1, 2, 6).

- Compute the distance d(u, v).
- Compute cos θ, where θ is the angle between u and v.

**(e) Projection of One Vector onto Another**

Using the same vectors from (d):

Compute the projection of u onto v.

### Source and Attribution
- **Primary Source**: Schaum's Outline of Linear Algebra, Fourth Edition (Schaum's Outline Series) by Seymour Lipschutz, Marc Lipson
- **Related Materials**: Linear Algebra Done Right by Sheldon Axler

### Motivation and Context

**Why This Matters:**

These operations (dot product, norm, angle, projection) are the geometric backbone of linear algebra.

**Relevance to ML/DL/AI:**

In machine learning, they underlie:
- **Cosine similarity** for measuring similarity of embeddings
- **Euclidean distance** used in k-NN and clustering
- **Projections** used in least-squares regression and dimensionality reduction

**Theoretical Significance:**

Conceptually, they train you to think of vectors as points and directions in space, not just lists of numbers.

### Hints and Guidance

**Consider:**

- **Dot product in ℝⁿ**: u · v = u₁v₁ + u₂v₂ + ... + uₙvₙ
- **Orthogonal** means u · v = 0. Use this to solve for k in (c).
- **Norm**: ||u|| = √(u · u)
- **Distance**: d(u, v) = ||u − v||
- **Angle**: cos θ = (u · v) / (||u|| ||v||)
- **Projection**: proj_v(u) = [(u · v) / ||v||²] v

For (d) and (e), compute u · v, ||u||², ||v||² once and reuse them.

### Discussion Space

**Questions:**
- **Clarify**: what does it mean geometrically that u and v are orthogonal in (c)?
- **Compare**: in (d), is the angle acute or obtuse? Check the sign of u · v.
- **Reflect**: in (e), is the projection shorter or longer than v? Why?

**Initial Observations:**
- The dot product captures how much two vectors "align"
- Zero dot product means perpendicular vectors
- Distance measures separation in space
- Projection finds the component of one vector along another

### Status Tracking
- **In Progress**: TBA

### Solutions Available
| Participant | Solution Link | Date Submitted | Notes |
|-------------|---------------|----------------|-------|
| Phanie's Mom | [View](https://github.com/lymphoidcell/daily-math/blob/main/Solutions/Phanie's%20Mom/Phanie's%20Mom%20-%20DAY%204.png) | November 14, 2025 | - |
| Phanie | TBA | November 14, 2025 | [📓 Chapter 1 Introduction to Vectors in ℝⁿ and ℂⁿ](https://example.com) |
| TBA | TBA | TBA | TBA |

### External Resources
| Source | Topic | Brief Description |
|--------|-------|-------------------|
| TBA | TBA | TBA |
