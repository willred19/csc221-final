# csc221-final
Final Exam programming challenge

Create a set of scripts that do the following with the file:
'nasa.tsv'

- Provides a list of unique hosts
- Provides a list of the most popular URLs


cat nasa.tsv| awk '{ print $1 }' | sort | uniq

With this code I :grabbed the first column using awk
sorted with uniq it to get rid of all the duplicate hosts.

