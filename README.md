blurry-password-requirements
============================

Permit/deny passwords by complexity level; not annoying minimum requirements (such as !@#!% characters or caps) - By [@drewhammond](https://github.com/drewhammond)

Overview
--------

The purpose of this plugin is to do away with the ridiculously annoying "minimum password requirements" based on primitive
standards, and instead use the real-world complexity of a password to permit or deny its use.

*For the purposes of this plugin, complexity is defined by the number of days it would take a hacker to bruteforce the user's password.*

This is my first GitHub project so bear with me. 

Usage
-----

@todo

Background
----------
Nothing pisses me off more than seeing the error message: *"Password does not meet minimum requirements. Please include at least 1 upper-case and 1 non-alphanumeric character."*

While it's true that certain passwords (i.e. dictionary words), are inherently insecure, it's unfair to punish all passwords that don't meet
traditional password complexity requirements.

For example, take the following passwords into consideration: 

1. tjgodantilurfkyfpmbfgqzj 
2. u4Eng25~

The first password is 24 characters long, but since it consists of all lower-case, alphabetical letters, it's rejected by thousands of websites on the internet.

The second password is 8 characters long, but is deemed "secure" with its upper- and lower-case letters, numeric, and non-alphanumeric characters. 

Is the second password inherently more secure? **Nope.**

The first password would take approximately 72,144,905,444,348,540 years to crack using a modern desktop computer while the second password would take just under 5 days.