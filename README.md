# password_strength_meter
Hi, would you be able to help design and implement an efficient PIN strength meter? It would be similar to how a password strength meter works but you'd need to know how to blacklist the common PINs and not so common PINs. PINs can be 4 digits as numbers or 6 or 8 digit, we can consider 4 digits. The PIN meter needs to be able to blacklist common PINs and only store good PINs. So we may have a solution for a non-trivial solution of the javascript web browser code and a trivial solution as well which not so efficient. The task will require research, I have gathered some papers which you could use to help come up with some of the idea's and background behind password strength meters, then choose which algorithms or any other efficient techniques you use to come up with the solution you choose to make the size of the code small as possible (efficient). In regards to common PINs, it could be 1234, 2345, 1111, 0000, date of birth year, date of birth date as well as month (DDMM), and some others so you can find on google these common PINs and then come to a conclusion and set out some ruling what these common PINs are and blacklist them, but PIN strength meter will either say PIN is very weak, weak, moderate, strong, very strong or weak, moderate, strong with a bar and maybe some tip on good PIN principle.

Let me know, thankyou..


1122 may be bad? (repetitive digits)
1234 may be bad? (next number after the next number)
4321 may be bad? (backwards minus one number)
0112 may be bad? (01-31 of DD (date of person being born) or 01-12 of MM (month persons born)
1999 may be bad? (A range when persons born year wise which idk can be lets say 1900-2020)

https://www.my1login.com/resources/password-strength-test/
