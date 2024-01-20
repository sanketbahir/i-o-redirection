# i-o-redirection

# To put the input content in a file, use the following command: 
hostname > filename

# Note: The above command will overwrite the content in the file.
# If you want to append the input, use the following command:
hostname >> filename

# To handle errors and redirect them to a separate file, use the following syntax:
cd in-out-Redirect.txt 2> error_file

# The above command redirects standard error (stderr) to the specified error file.

# To store the list of directories in a file, use the following command:
ls > filename

# Note: The above command will overwrite the content in the file.
# To append the list of directories, use the following command:
ls >> filename

# To save both the results of 'ls' and 'history' commands in the same file, use:
history >> filename

# To redirect errors without displaying them in the terminal, use:
mkd 2> filename

# The above command saves errors in the specified file without showing them in the terminal.

# To append errors to the same file, use the following command:
kkl 2>> filename

# To save both the output and errors of the 'ls' command in a file, use:
ls &>> filename

# The above command will append both standard output (stdout) and standard error (stderr) to the file.

# To end or redirect the input for 'cat', use the following command with a delimiter:
cat > file5 <<eof
# Enter your content here
eof
