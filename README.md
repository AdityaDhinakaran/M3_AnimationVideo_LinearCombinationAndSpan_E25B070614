# Linear Algebra and Calculus (M3) — Internal Assessment

## Project Option 1: Animation Video

**Topic:** Linear Combination and Span  
**Student Name:** Aditya Dhinakaran  
**Student ID:** E25B070614  
**Video Format:** 16:9 landscape · 1080p Full HD · MP4  
**Video Duration:** 5 minutes 40 seconds (below the strict 7-minute limit)

## 1. Project Overview and Learning Objective

**Learning objective:** By the end of this video, viewers should be able to explain how scalar multiples of vectors are added to form a linear combination, describe the span as the set of all such combinations, and use examples to determine whether a set of vectors spans a line or the whole plane.

The animation introduces the two ideas visually with vector diagrams, worked coordinates, and a comparison between a single vector and pairs of parallel or non-parallel vectors.

## 2. Deliverables in This Repository

| File or folder | Description |
| --- | --- |
| `Video.mp4` | Final 1080p video, including the opening title card with name and ID and a closing card with takeaways, reference, and AI disclosure. |
| `Storyboard.pdf` | Six-scene storyboard. |
| `Code/Linear Combination and Span.html` | Interactive animation source. The animation logic is written in **inline JavaScript** inside the HTML file. |

## 3. Six-Scene Video Structure

1. **Introduction:** Presents linear combination and span as two core ideas in linear algebra.
2. **Linear combinations:** Defines scalar coefficients and demonstrates scaling vectors.
3. **Worked example:** Computes `2u + 3v = (7, 18)` for `u = (2, 3)` and `v = (1, 4)`.
4. **Span:** Defines the span as all possible linear combinations and illustrates the span of one nonzero vector.
5. **Geometric examples:** Compares parallel and non-parallel vectors and shows how the standard basis spans `ℝ²`.
6. **Conclusion:** Distinguishes the operation of taking a linear combination from the set of all results, then summarizes the ideas.

## 4. Mathematical Examples

For `u = (2, 3)` and `v = (1, 4)`,

```text
2u = (4, 6)
3v = (3, 12)
2u + 3v = (4 + 3, 6 + 12) = (7, 18)
```

The span of vectors `u` and `v` is the set of every linear combination `a·u + b·v`, where `a` and `b` are real numbers. In `ℝ²`, two non-parallel vectors span the plane; parallel vectors span a line through the origin. The standard basis vectors `(1, 0)` and `(0, 1)` span `ℝ²` because `a(1, 0) + b(0, 1) = (a, b)`.

## 5. How to Run the Interactive Source

Open `Code/Linear Combination and Span.html` in a modern browser and select **Play**. The animation can be paused, replayed, and navigated by scene. The page uses inline JavaScript and requires no separate JavaScript file or package installation. The optional **Read captions aloud** control uses the browser’s speech synthesis.

## 6. Viva / Q&A Preparation

**Q1: What is a linear combination?**  
A linear combination scales each vector by a scalar and adds the resulting vectors, such as `a·u + b·v`.

**Q2: What is the span of a set of vectors?**  
It is the set of all vectors that can be formed as linear combinations of the given vectors.

**Q3: Why do two non-parallel vectors span the plane `ℝ²`?**  
They point in independent directions, so appropriate scalar multiples can combine to produce any coordinate pair in the plane.

## 7. Reference and AI Disclosure

**Reference:** MIT OpenCourseWare, 18.06SC Linear Algebra, “Independence, Basis, and Dimension”: <https://ocw.mit.edu/courses/18-06sc-linear-algebra-fall-2011/pages/ax-b-and-the-four-subspaces/independence-basis-and-dimension/>

**AI disclosure:** AI assistance was used to prepare the storyboard and repository documentation. The supplied animation source and video soundtrack were retained. Inline JavaScript is used in the HTML animation source.
