##  [📁 Notion Page Link](https://www.notion.so/Daily-Math-Problem-DAY-8-2ac6760c95538109b742c61a43612c46?source=copy_link)

---

# Daily Math Problem - DAY 8

### Problem Metadata
- **Date:** 2025-11-18
- **Problem Number:** #8
- **Topic:** Vector Algebra — Cross Product (Determinant Method & Component Formula)
- **Category:** Machine Learning Math / Linear Algebra
- **Difficulty Level:** Beginner → Intermediate
- **Problem Curator:** Phanie

### Prerequisites
- 3D vector notation
- Determinant expansion
- Basis vectors (i, j, k)
- Cross-product formula

### Problem Statement

Let the vectors u and v be:

```
u = 5i − 2j + 4k
v = −1i + 3j + 2k
```

**(a) Cross Product via Determinant**

Compute the cross product u × v using the determinant form:

```
u × v = | i   j   k  |
        | 5  -2   4  |
        |-1   3   2  |
```

Expand along the first row to obtain the components.

**(b) Cross Product via Component Formula**

Rewrite u = [5, −2, 4] and v = [−1, 3, 2], and compute:

```
u × v = (u₂v₃ − u₃v₂, u₃v₁ − u₁v₃, u₁v₂ − u₂v₁)
```

Verify that this matches your answer in part (a).

### Remark: Basis Cross Products

Use the identities:

```
i × j = k,  j × k = i,  k × i = j
j × i = −k, k × j = −i, i × k = −j
```

These ensure correct signs during the determinant expansion.

### Source and Attribution
- **Primary Source:** Schaum's Outline of Linear Algebra, Fourth Edition (Schaum's Outline Series) by Seymour Lipschutz, Marc Lipson
- **Related Materials:** Linear Algebra Done Right by Sheldon Axler

### Motivation and Context

**Why This Matters:**

Cross products matter in ML whenever 3D geometry is involved:

**Relevance to ML/DL/AI:**
- 3D computer vision → surface normals, depth reconstruction
- Robotics and pose estimation → rigid-body rotations, torque direction
- Differentiable rendering → NeRF, mesh gradients
- Point-cloud networks → directional features, local frames

**Theoretical Significance:**

The cross product encodes orientation, area, and orthogonal directions, making it fundamental in geometric learning.

### Hints and Guidance

**Consider:**

- For (a): Expand the 3×3 determinant along the first row

- For (b): Be careful with signs in the component formula:

```

  (u₂v₃ − u₃v₂, u₃v₁ − u₁v₃, u₁v₂ − u₂v₁)
  
```

- Expect both methods to yield the same vector

### Discussion Space

Questions:
- Why does the cross product represent an area-weighted normal?
- Why is its direction perpendicular to both u and v?
- When is u × v = 0?
- How does the right-hand rule relate to orientation in ML/robotics?

Initial Observations:
- The cross product is only defined in ℝ³
- The result is always orthogonal to both input vectors
- The magnitude equals the area of the parallelogram spanned by u and v

### Status Tracking
- In Progress: TBA

### Solutions Available
| Participant | Solution Link | Date Submitted | Notes |
|-------------|---------------|----------------|-------|
| Phanie's Mom | TBA | November 18, 2025 | - |
| Phanie | TBA | November 18, 2025 | [📓 Chapter 1 Introduction to Vectors in ℝⁿ and ℂⁿ](https://example.com) |
| TBA | TBA | TBA | TBA |

### External Resources
| Source | Topic | Brief Description |
|--------|-------|-------------------|
| [Khan Academy](https://www.khanacademy.org/v/linear-algebra-cross-product-introduction) | Cross product basics | Introduction to the cross product. Created by Sal Khan. |
| [3Blue1Brown](https://www.youtube.com/watch?v=LyGKycYT2v0) | Dot products and duality | Dot products are a nice geometric tool for understanding projection. This video explores the deeper connection between numerical computation and geometric interpretation through linear transformations. |
