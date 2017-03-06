# truncate-files-in-directory

This node.js program will truncate all filenames in a directory. It will make potential duplicate filenames web safe by coverting the 
filename to lowercase and replacing spaces with &ndash;.

To use the program:

1. Place all file in the truncate-files-in-directory directory.
2. Run node index.js (length) (fileType)
3. The argumnets in parenthesis are optional and set to a default of (length = 6) and (fileType = .pdf).
