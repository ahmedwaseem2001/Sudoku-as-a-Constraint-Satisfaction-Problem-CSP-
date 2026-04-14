This project is a Sudoku Solver built using the Constraint Satisfaction Problem (CSP) approach in Artificial Intelligence. It solves a 9×9 Sudoku puzzle by treating each cell as a variable and applying constraints so that no number repeats in any row, column, or 3×3 grid.
The solver uses Backtracking Search along with smart techniques like AC-3 (Arc Consistency), Forward Checking, and the MRV heuristic. These methods help reduce the search space and solve puzzles efficiently, even for harder levels.
🚀 Features
Solves 9×9 Sudoku puzzles 
Supports easy to very hard levels 
Uses CSP-based techniques 
Applies Backtracking, AC-3, Forward Checking, and MRV 
Shows performance (calls and failures) 
▶️ How to Run 
Add puzzles in .txt files (e.g., easy.txt) 
Run: python solver.py 
📊 Output 
Displays the solved Sudoku grid along with backtracking calls and failures. 
👨‍💻 Author 
Ahmed Waseem
