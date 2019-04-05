# CodePathWP

# Exploit 1: XSS
Rsource: https://www.youtube.com/watch?v=3iCyk7d_1h8

Summary:
With a maliciously crafted comment, a WordPress post was vulnerable to cross-site scripting. 
CVE: 2019-9787
Fixed in Version: 4.2.23

## Steps to Recreate:
1) Generate WordPress version 4.2
2) Create a post
3) Visit published post, add comment containing XSS
<img src="https://github.com/Ethefirst/CodePathWP/blob/master/XSS%204.2.png">
