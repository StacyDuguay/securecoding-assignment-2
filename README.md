# Do these results match what you found in your previous peer review? Why or why not?

Kind of but not perfectly, bandit found three vulnerabilities which included using
http, os injection, and the db injection vulnerabilities.

## Do you think they caught all the vulnerabilities present in the code? Why or why not?

No they didn't catch everything. Codeql didn't seem to catch anything just using the base settings,
bandit scan caught some but not all which is to be expected, and superlinter caught a bunch of formatting issues
which is what it was supposed to do. overall they caught some but missed others which is expected since no tool can
guarantee 100% coverage.

## Why is using multiple code scanners better than using one?

Using multiple is always better because some tools are designed to find specific vulnerabilities and no
single tool covers every type of vulnerability.
