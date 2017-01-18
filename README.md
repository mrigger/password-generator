# PasswordGenerator

	$ password 3 4
	jF6f_4qu0_ed!!

Password generator is a command line tool that generates random passwords. Passwords generated by this program consist of a given number of chunks separated by underscores, each containing a given length of characters (of which there are 64 in total).

	$ password 2 5
	jF6f4_qu0ed

## Usage

Password Generator takes two to three command line arguments, all of which are integers.

| Argument  |                             Description                              |
|:---------:|:--------------------------------------------------------------------:|
|     1     | The number of chunks in the password                                 |
|     2     | The length of each chunk                                             |
|     3     | (optional argument, defaults to 1) A number of passwords to generate |