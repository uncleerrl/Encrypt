De/En-Crypt 

(ONLY TESTED IN KALI LINUX)
1-Save as DeEn-Crypt in a location you know the file path-
2-Open Bash, Terminal, Terminator, or you favorite CLI, navigate to the directory in which ####	DeEn-Crypt is stored with (cd "/home/lostandfound/") replace "/home/lostandfound/" 
with the folder "DeEn-Crypt" is stored in. 
3-Type "sudo chmod +x DeEn-Crypt"
4-Type "./DeEn-Crypt --help" to display options
5-To Encrypt Example "./DeEn-Crypt -e [File]"
6-Enter Strong Password
7-Verify Password
8-To Decrypt "./DeEn-Crypt -d [File.aes]"
9-Enter in Password to Decrypt
10-Decypted File will be in the same folder as the encrypted file. 

-also working on a hashing function that hashes the encryption key and the one key is used to check the other but none of the keys know exactly where they came from. 3 levels the first knows about the 2nd, the 2nd knows about the 3rd but not enough to get back to the first. Layering hashes and encryption. still a work in progress 