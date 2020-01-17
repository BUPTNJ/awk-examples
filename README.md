# awk-examples
using awk to extract information from text like html to make a csv file.

# warning
some old versions may not support match(a,b,c), you can install gawk to replace it.

# how to use?
cat 180801.html | gawk -f cmd.txt >180801.csv
