# Project Title

Python Mailing Script

## Introduction

This is a script written to send e-mail to multiple contacts stored in a file. It is supposed to send the e-mail to each of the contacts with a "Dear [Name]" at the top of the message followed by the message body.

The contacts are stored in myContacts.txt file and the message in message.txt file.

### Prerequisites


To make the project functioning make sure that Python 3 is installed in the system.
To download Python use the following link : https://www.python.org/downloads/

I will suggest to use Git Bash to run the python program. Any other command line will also be fine.


### Steps

To set the data in myContacts.txt follow the steps below:

```
1. Open myContacts.txt file 
2. There will be two columns present in a single row.
3. The first column is for the name oi the person to whom the mail is being sent.
4. The second column is for the email id of the person to whom the mail is being sent.
```

To set the login information to your own account through which the emails will be sent, follow the steps below:


```
1. At line 8 initialize the variable 'youraddress' with your gmail account for sending the mails.
2. At line 9 initialize the variable 'yourpassword' with the password of your account.  
```

To set the login information to your own account through which the emails will be sent, follow the steps below:


```
1. At line 8 initialize the variable 'youraddress' with your gmail account for sending the mails.
2. At line 9 initialize the variable 'yourpassword' with the password of your account.  
```

## Running the program

To run the program go the folder 'Mail' and type the command : py ./mail.py 

If the setup of python has been right then the program will run.

### Account Login Issue

It might happen that the script may not run because of account login process being blocked by Gmail.
For this, follow the steps below :

```
1. Login to your account.
2. Go to https://myaccount.google.com/intro/security
3. On the left side select apps with account access.
4. Scroll down and turn on the 'Allow less secure apps' option.
5. Done!
```




## Authors

* **Suyash Awasthi** - *Initial work* - [suyash2810](https://github.com/suyash2810)

## License

This project is licensed under the MIT License - see the [License.md](LICENSE.md) file for details

