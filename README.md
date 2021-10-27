# generateIndex.py
 Generate index.html for a directory. Written in python3.
 
 Usage:
 
 python3 generateIndex.py [options] [indexFrom]
 
 Options:
 
 -r, --recursive 
         recurse into subdirectories, generating index.html files for every subdirectory encountered.
	 
 -f, --filter by file type (i.e., --filter "*.iso")
	   
 -v, --verbose 
         verbosely print every file processed. Use with caution in combination with --recursive and when  processing directories which contain many files. This option can take a lot of time if the file tree is large. But the difference is usually not noticeable for smaller file trees or individual directories. 
	   
 [indexFrom] 
         (optional) first positional argument may specify the starting point of the index. if left blank, files will be indexed relative to the current working directory (recommended).
