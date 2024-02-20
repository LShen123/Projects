FR1: The program acts like a simple interpreter for a scripting/command language. The file includes commented lines that are recognized by either the character ‘#’, as the start character of the line; or by “//”, as the first two characters of the line. The program keeps track of the total number of lines read, the number of non-commented lines, the line of the maximum length, the number of words, and the word of maximum length.  

FR2: The program counts the number of lines, the number of non-blank lines, the number of words that contain 5 or less characters, the number of words that contain more than 5 characters, the number of names (special names), and the number of unsigned integers, seen in the file.

FR3: 
The program accepts one or more command line arguments. The format of the command line arguments is specified as follows:
The first argument must be a file name.
The optional arguments are specified for one or more of the following flags:
“-all”: The program prints out each character of a category and the number of times it has been seen. 
“-L”: The program prints out each letter and the number of times it has been seen only.
“-D”: The program prints out each digit and the number of times it has been seen only.
“-P”: The program prints out each punctuation character and the number of times it has been seen only.
