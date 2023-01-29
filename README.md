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
### Step 7:
Print the output.
## PROGRAM:
```python
developed by: J.NETHRAA
registered number: 22006789
with open('first.txt','r') as firstfile, open('second.txt','a') as secondfile:
    for line in firstfile:
             secondfile.write(line)
```

### OUTPUT:
![image](https://user-images.githubusercontent.com/121215786/215334315-2dcc1d05-39ba-4755-8371-4c52b985ba78.png)

![image](https://user-images.githubusercontent.com/121215786/215334343-12dd7207-b414-4ce9-ac08-b05e9a17e923.png)

![image](https://user-images.githubusercontent.com/121215786/215334464-36da5f26-2198-4455-877c-f716cc2ed830.png)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
