Unique Passwords
================

[UPDATE] In the [older version][5], the password is plain text, updated that to hidden (password field).

You can use the [password generator][1] to create strong but unique passwords for all your web accounts. It internally uses the bcrypt algorithm for hashing.

###How to Use

Go to [ctrlq.org/passwords][1] to test a live version of the password generator.

1. Enter the account login of any website in the User Name field (case insensitive)
2. Put the website name in the domain field (case insensitive). Do not include any suffix or prefix in the domain name - for instance, use google and not google.com.
3. Choose a password length.
4. Think of a secret passphrase - do include digits, letters and symbols in your passphrase and never share it with anyone. 

Just write the passphrase (case insensitive) in the input field and hit generate to get you your unique password for that particular site.

### Mobile Version

The password generator uses [responsive design][2] and therefore works across all screens including mobile phones and tablets. All it requires is a web browser with JavaScript enabled. 

### Offline Version

You can also download the password generator for offline use. Just extract the zip file and double-click index.html to launch program. For added security, you may [password-protect the folder][3] or place the folder inside Dropbox and [secure with 2-factor verification][4].

### Authors

* Amit Agarwal: http://twitter.com/labnol
* Digital Inspiration: http://www.labnol.org/

### Credits

* SuperGenPass [https://github.com/cmcnulty/SuperGenPass](https://github.com/cmcnulty/SuperGenPass)
* BCrypt [http://en.wikipedia.org/wiki/Bcrypt](http://en.wikipedia.org/wiki/Bcrypt)

#### License

Copyright 2012-2013 Digital Inspiration
Licensed under the Apache License,
Version 2.0: http://www.apache.org/licenses/LICENSE-2.0

[1]: http://ctrlq.org/passwords/
[2]: http://www.labnol.org/internet/responsive-web-design-faq/21361/
[3]: http://www.labnol.org/software/password-protect-folders-files/14323/
[4]: http://www.labnol.org/internet/secure-dropbox-account/25096/
[5]: https://github.com/labnol/passwords
