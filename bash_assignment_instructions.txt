// Bash/Unix Command Line Tools Workshop Assignment
// In this assignment, you'll apply your 
// knowledge of Unix commands to work with files, directories, 
// and text processing. You will navigate directories, 
// create and edit scripts using nano, and manipulate text 
// data with tools like grep, awk, and sed. 

// For each exercise, write and submit a short explanation 
// and a screenshot of your work.

// Part 1: Directory and File Navigation
// 1. Create a Project Directory Structure
// Create an assignment directory called assignment.
// Inside assignment, create the following subdirectories:
// - scripts
// - data
// - logs


// 2. Create a Data File
// In the data directory, create a file called sample.txt 
// that contains 50 lines of text. 
// Each line can be a simple sentence or a sequence 
// (e.g., "Line 1: This is line 1").

// Part 2: Script Writing with Nano
// 1. Create a Script File
// Using nano, create a script called file_checker.sh in the scripts directory.

// 2. Script Requirements
// The script should accept one argument.
// Check whether the argument is:
// A file: Print "[argument] is a file."
// A directory: Print "[argument] is a directory."
// Neither: Print "[argument] does not exist."

// 3. Make the Script Executable
// chmod +x file_checker.sh
// Test your script:
// Run your script with different arguments (e.g., an existing file, a directory, and a non-existent path).

// Part 3: Text Processing with grep and awk
// Exercise 3A: Using grep
// 1. Create a Log File
// In the logs directory, create a file named system.log.
// Populate it with at least 20 lines of sample log entries. 
// Each line should contain a mix of keywords like "error", "warning", and "info". 
// You may manually create some entries or use nano.

// 2. Search for Errors
// Use grep to search for lines containing the word "error".