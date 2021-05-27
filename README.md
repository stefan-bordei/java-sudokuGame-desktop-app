# Sudoku Desktop App implementation in Java
Project I did by following the tutorial made by **Ryan Kay** in order to practice coding in *Java* and familiarize myself with *javafx* and practice OOP principles. 

## Project contains:
- `*Problem Domain Classes*`
	- SudokuGame 
	- Coordinates with Hashing, IStorage
- `*Constants w/ Enums & static final variables*` 
	- GameState
	- Messages
	- Rows 
- `*Application Container/Entry Point*` 
	- SudokuApplication
	- Main 
- `*User Interface w/ Java Interfaces*` 
	- IUserInterfaceContract
	- EventListener
	- View 
- `*User Interface*` 
	- Custom JavaFX TextField 
- `*User Interface*` 
	- UserInterfaceImpl
	- Managing 81 TextFields w/ HashMap
- `*Control Logic*`
	- Implementing EventListener similar to MVP/MVC
- `*Computation Logic*`
	- SudokuUtilities static Helper Methods 
- `*Computation Logic*`
	- GameGenerator Algorithms for generating a new solvable Sudoku Game 
- `*Computation Logic*`
	- SudokuSolver Algorithm for Solving a Sudoku Game 
- `*Computation Logic*` 
	- Entry Point To Back End & Algorithms for Validating a Sudoku Game for Completion 
- `*Build Logic*`
	- SudokuBuildLogic for "separating configuration from use" -Martin Fowler
- `*Persistence/Data Storage*` 
	- LocalStorageImpl for storing data on the local filesystem
