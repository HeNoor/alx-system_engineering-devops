**script that prints “Hello, World”**

echo 'Hello, World'

**displays a confused smiley "(Ôo)'**

echo "(Ôo)'\

**Display the content of the /etc/passwd file**

cat /etc/passwd

**Display the content of /etc/passwd and /etc/hosts**

cat /etc/passwd /etc/hosts

**Display the last 10 lines of /etc/passwd**

tail /etc/passwd

**Display the first 10 lines of /etc/passwd**

head /etc/passwd

**displays the third line of the file iacta**

head -n 3 | tail -n 1

**creates a file named exactly \*\\'"Best School"\'\\*$\?\*\*\*\*\*:) containing the text Best School**
echo "Best School" > "\*\\\'\"Best School\"\'\\\*$\?\*\*\*\*\*:)"

**writes into the file ls_cwd_content the result of the command ls -la**

ls -la > ls_cwd_content

**duplicates the last line of the file iacta**

tail -n 1 iacta >> iacta

**deletes all the regular files (not the directories) with a .js extension that are present in the current directory and all its subfolders.**

find . -type f -name "*.js" -delete


