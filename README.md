# Backup-and-Encryption-Script
This is a Python script that allows you to back up a directory and encrypt its contents using the Fernet encryption algorithm from the cryptography library. You can also restore the backup and decrypt its contents using the same encryption key.


Usage:
To use this script, you need to have Python 3 and the cryptography module installed. 

You can run the script using the command-line interface. The script accepts the following arguments:

directory: the directory to back up or restore.

key: the encryption key.

-d or --decrypt: an optional flag that specifies whether to restore from backup.
