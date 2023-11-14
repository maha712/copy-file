# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
First we need to open the required file form which we need to copy the text.Again using the with keyword to open the empty file.

### Step 2: 
Using keyword "with" to open the requied file.
 
### Step 3: 
Again using the with keyword to open the empty file.

### Step 4:  
The empty file is open by using 'W' which is used to write only.

### Step 5: 
The four function is used to take each line from the main file.

### Step 6: 
The four function is used to take each line from the main file.

### step 7:
Print the output.

## PROGRAM:

Developed by: Mahalakshmi.k

RegisterNumber: 22009204

with open("git.txt","r") as f1:

    with open("git.txt","a") as f2:
    
        for line in f1:
        
            f2.write(line)
            

### OUTPUT:
![1](https://github.com/maha712/copy-file/assets/121156360/56be8ad0-a5aa-42c3-b582-ac2feca98b89)
![2](https://github.com/maha712/copy-file/assets/121156360/904d034d-ca67-46a3-992f-2aba8bd68fb7)
![3](https://github.com/maha712/copy-file/assets/121156360/e011501c-6668-45b9-bb58-9bd129072b99)
![4](https://github.com/maha712/copy-file/assets/121156360/9e22bf00-5fd9-467a-b791-ec1566fff8ed)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
