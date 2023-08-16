# Computational Resources

## Setting up TSCC account
### Generating an SSH Key using ssh-keygen

#### MAC/LINUX INSTRUCTIONS

Open the Terminal program. On a Mac, it can be found under Macintosh HD ▸ Applications ▸ Utilities.

Once in the terminal, enter the command:

ssh-keygen
You will be prompted to provide a location to save the key. We recommend accepting the default location (shown in parenthesis) by pressing enter. In the example below, the default save location is used.

You will be prompted to enter a passphrase. Pressing enter without entering a passphrase is generally fine unless you want extra security. Note: if you use a passphrase, you will be prompted to enter it whenever you use the key. Also, if you forget your passphrase, it cannot be recovered and you will need to make a new key. The example below uses no passphrase.

After following steps 1-4 above, your Command Prompt should be similar to the example on the following page:

computer-name:~ user-name$ ssh-keygen

Generating public/private rsa key pair.

Enter file in which to save the key (/Users/user-name/.ssh/id_rsa):

Enter passphrase (empty for no passphrase):

Enter same passphrase again:

Your identification has been saved in /Users/user-name/.ssh/id_rsa.

Your public key has been saved in /Users/user-name/.ssh/id_rsa.pub.

The key fingerprint is:

SHA256:(string of numbers and letters) user-name@computer-name.local

The key's randomart image is:

+---[RSA 2048]----+

| |

| |

| |

| |

| |

+----[SHA256]-----+

5.Print the file to the terminal using the command "cat". For example (please replace your username in the command below):

cat "/Users/user-name/.ssh/id_rsa.pub"

The output will look similar to the example below:

$ cat "/Users/user-name/.ssh/id_rsa.pub"
ssh-rsa (4 lines of letters and numbers) user-
name@computer-name
|

6.Copy and paste the entire rsa public key (the portion highlighted above), and send it to services@arimagenomics.com. Please send only the public key, not the private key. The private key is used by the SFTP client for authentication. Never send it to someone else.

#### WINDOWS 10 INSTRUCTIONS

Open the Command Prompt program. On Windows 10, it can be found under Start ▸ Windows System.

Once in the command prompt, enter the command

ssh-keygen
You will be prompted to provide a location to save the key. We recommend accepting the default location (shown in parenthesis) by pressing enter. In the example below, the default save location is used.

You will be prompted to enter a passphrase. Pressing enter without entering a passphrase is generally fine unless you want extra security. Note: if you use a passphrase, you will be prompted to enter it whenever you use the key. Also, if you forget your passphrase, it cannot be recovered and you will need to make a new key. The example below uses no passphrase.

After following steps 1-4 above, your Command Prompt should be similar to the following example:

C:\Users\user-name>ssh-keygen

Generating public/private rsa key pair.

Enter file in which to save the key (C:\Users\user-name/.ssh/id_rsa):

Enter passphrase (empty for no passphrase):

Enter same passphrase again:

Your identification has been saved in C:\Users\user-name/.ssh/id_rsa. Your public key has been saved in C:\Users\user-name/.ssh/id_rsa.

The key fingerprint is:

SHA256:(string of numbers and letters) user-name@computer-name

The key's randomart image is:

+---[RSA 2048]----+

| |

| |

| |

| |

| |

+----[SHA256]-----+

5.Print the file to the Command Prompt using the command "type". For example (please replace your username in the command below):

type "\Users\user-name.ssh\id_rsa.pub"

The output will look similar to the example below:

$ type "\Users\user-name.ssh\id_rsa.pub"
ssh-rsa (4 lines of letters and numbers) user-
name@computer-name
|

6.Copy and paste the entire rsa public key (the portion highlighted above), and send it to TechSupport@arimagenomics.com. Please send only the public key, not the private key. The private key is used by the STFP client for authentication. Never send it to someone else.




## Setting up AWS account

##

