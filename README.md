# python_password_checker

## Explanation 

This project uses Troy Hunt's Have I Been Pwned API to check whether the first five characters of the SHA1 generated password have been leaked in the past. The code will execute telling you the number of times your password has been leaked and whether it should be changed. 


## Usage

You will need a stable internet connection to run this code as it is connecting to an external API.

Go to main.py download the file and run the following command on terminal for Mac or equivalent on Windows/Linux

```bash
python3 {main.py_file_path} {input_password_to_check}
```
If the above command does not work follow the three steps:

1. Download main.py and move it to your desktop 
2. Then run 
```bash
cd Desktop/
```
3. And then run 
```bash
python3 main.py {input_password_to_check}
```

 The code will successfully compile and tell you how many times the password was found and whether you should change your password 
 
 This is the most secure way to check if your password has been leaked.
 
 Follow me on Linkedin https://www.linkedin.com/in/aarav-khanduja-0467191b0/

 
