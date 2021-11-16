# PasswordList

Collection of passwords from various dumps, breaches, and custom lists.


Files are in master branch as split zip files. Recombine and profit!

Files are hosted via LFS. Use the following (or simiilar) to obtain the files to recombine:

    wget https://github.com/Cyb3r4rch3r/PasswordList/blob/master/Combined.zip.001

    wget https://github.com/Cyb3r4rch3r/PasswordList/blob/master/Combined.zip.002

    wget https://github.com/Cyb3r4rch3r/PasswordList/blob/master/Combined.zip.003


This should download and recombine in one step:
        
        for i in {1..3}; do echo "https://github.com/Cyb3r4rch3r/PasswordList/raw/master/Combined.zip.00$i" >> PassList.txt; done; wget -i PassList.txt; p7zip x Combined.zip.001
