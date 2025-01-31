# Da Vinci's Tree
## [Assignment 2 - The Fluxus movement](https://github.com/charlieroberts/imgd-5010-s24/blob/main/assignment2-instructions.md)
### Instructions:

*"All the branches of a tree at every stage of its height when put together are equal in thickness to the trunk. All the branches of a water at every stage of its course, if they are of equal rapidity, are equal to the body of the main stream.” - Excerpt from the notebook of Leonardo Da Vinci*

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;The premise of this project is to use p5.js to draw a fractal branching tree. The most prolific artistic model for depicting trees and tree growth is Da Vinci's, where until being [somewhat disproven](https://www.pnas.org/doi/10.1073/pnas.2215047120), the model was also applied for biomechanical, fluid dynamic, and physical stress modeling. 

The formula for this representation is written as:&nbsp;&nbsp;&nbsp;π * $r^{2} _ {1}$ = π * $r^{2} _ {2}$ + π * $r^{2}_{3}$ + etc... which is simplified and updated by replacing constant exponent 2 for variable exponment α and by removing all instances of π:&nbsp;&nbsp;&nbsp; $r^{α} _ {1}$ = $r^{α} _ {2}$ + $r^{α} _ {3}$ + etc... ($r^{α}$ = ∑ $r^{α} _{i}$ where i = 1, 2, ...)

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;NB:&nbsp;&nbsp;Variable $r _ {1}$ refers to the radius of the splitting trunk or branch, where $r _ {2}$, $r _ {3}$, and so on refer to the split trunk or branches. The variable exponent α represents values ranging from 1.8 and 3 in accordance with scientific study of tree species phenology in the centuries following Da Vinci's initial conjecture.

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;For this project, I'd like to use p5.js to draw a tree that splits into branches that continue to split, with more branches every split within vaguely naturalistic angles. Using the above formula, p5.js should be directed to render a tree that splits four times, where each splitting iteration splits into more branches that also split, and so on before terminaing in foliage.

![Top-Down](https://github.com/Wazbaz-the-Weary/Peter_L_Griffiths_Assignment_2/blob/main/Screenshot 2025-01-30 193826.png?raw=true)

### Program:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;https://editor.p5js.org/Wazbaz-the-Weary/sketches/GMUiMM_Kt
