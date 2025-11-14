## [📁 Notion Page Link](https://www.notion.so/Daily-Math-Problem-DAY-5-2ab6760c955381bba15cd6c4df0bea48?source=copy_link)

---

# Daily Math Problem - DAY 5

### Problem Metadata
- **Date**: 2025-11-15
- **Problem Number**: #5
- **Topic**: Geometry of Hyperplanes and Lines in ℝⁿ
- **Category**: Machine Learning Math / Linear Algebra
- **Difficulty Level**: Beginner
- **Problem Curator**: Phanie

### Prerequisites
- Vector subtraction
- Dot product and orthogonality
- Hyperplane equation form in ℝⁿ
- Parametric representation of lines

### Problem Statement

This problem explores plane geometry in ℝ³ and hyperplane/line geometry in ℝ⁴. Solve all parts.

**(a) Plane Geometry in ℝ³**

Let H be the plane in ℝ³ corresponding to the linear equation:

```
3x − 4y + 2z = 5
```

Points P = (2, −1, 0) and Q = (5, 2, 3) are solutions of this equation, so they lie on H.

1. Compute the directed vector v = PQ = Q − P
2. Let u = [3, −4, 2] be the normal vector of the plane. Verify orthogonality by computing u · v

**(b) Equation of a Hyperplane in ℝ⁴**

Find the equation of the hyperplane H in ℝ⁴ that:
- passes through the point P = (2, 1, −3, 4)
- is normal to the vector u = [7, −1, 5, −2]

Write the hyperplane in the form:

```
7x₁ − 1x₂ + 5x₃ − 2x₄ = k
```

and determine the value k by substituting point P.

**(c) Parametric Representation of a Line in ℝ⁴**

Let the line L ⊂ ℝ⁴ pass through P = (−1, 3, 0, 2) with direction vector u = [−4, 6, 1, 9].

1. Write the parametric form L(t) = P + tu
2. Find the coordinates of the point Q when t = 2

### Source and Attribution
- **Primary Source**: Schaum's Outline of Linear Algebra, Fourth Edition (Schaum's Outline Series) by Seymour Lipschutz, Marc Lipson
- **Related Materials**: 
  - Linear Algebra Done Right by Sheldon Axler
  - Hyperplanes in ℝ⁴
  - Geometry of vector equations
  - Parametric representations

### Motivation and Context

**Why This Matters:**

These problems operationalize core geometric machinery used throughout machine learning:

**Relevance to ML/DL/AI:**
- **Normal vectors** define decision boundaries (SVM hyperplanes)
- **Parametric lines** model gradient updates, ray casting, and direction-based optimization
- **Orthogonality** is central to PCA, embeddings, orthogonal projections, and stability of linear transformations

**Theoretical Significance:**

The problems reinforce how equations in ℝⁿ encode geometry, orientation, and constraints—foundational intuition for ML systems.

### Hints and Guidance

**For (a):**
- Subtract coordinates: Q − P
- A plane normal vector is orthogonal to every direction lying in the plane

**For (b):**
- Hyperplane equation coefficients = components of the normal vector
- Substitute P coordinates into the equation to solve for k

**For (c):**
- Parametric line: each coordinate follows xᵢ(t) = pᵢ + tuᵢ
- Evaluate at a specific t to obtain a concrete point

### Discussion Space

**Questions:**
- Why is the direction vector between any two points on a plane guaranteed to be orthogonal to the plane's normal vector?
- How does a hyperplane equation generalize the idea of a plane?
- What geometric shape does a line in ℝ⁴ represent?

**Initial Observations:**
- Normal vectors encode the "orientation" of hyperplanes
- Parametric forms give explicit trajectories through space
- Orthogonality checks validate geometric relationships

### Status Tracking
- **In Progress**: TBA

### Solutions Available
| Participant | Solution Link | Date Submitted | Notes |
|-------------|---------------|----------------|-------|
| Phanie's Mom | TBA | November 15, 2025 | - |
| Phanie | TBA | November 15, 2025 | [📓 Chapter 1 Introduction to Vectors in ℝⁿ and ℂⁿ](https://example.com) |
| TBA | TBA | TBA | TBA |

### External Resources
| Source | Topic | Brief Description |
|--------|-------|-------------------|
| TBA | TBA | TBA |
