# DeathRansom

## What is a ransomware?

A ransomware is malware that encrypts all your files and shows a ransom request, which tells you to pay a set amount, usually in bitcoins (BTC), in a set time to decrypt your files, or he will delete your files.

## How it works?

First, the script checks if it's in a sandbox, debugger, vm, etc, and try bypass it.                                                       
It then encrypts all files starting with the defined directory.                                                                          
Then, downloads the ransom request script, disable cmd, taskmanager and the registry tools.
