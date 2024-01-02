# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Get the file name to create user.
### Step 2: 
 Give a new file name to create a copy of a file content.
### Step 3: 
Read the file and close the file.
### Step 4:  

Now the content in the new file.
### Step 5: 
When done print"File Copied Successfully"
### Step 6: 
End the program
## PROGRAM:

```
'''
#Program to copy the file.
#Developed by:SUBHASHRI R
#RegisterNumber:212223230219
'''
print("Enter the name of source file: ")

sFile=input()

print("Enter the name of target file: ")

tFile=input()

fileHandle=open(sFile,"r")

texts=fileHandle.readlines()

fileHandle.close()

fileHandle=open(tFile, "w")

for s in texts:

    fileHandle.write(s)

fileHandle.close()

print("\nFile Copied Successfully!")

```




### OUTPUT:


![Screenshot 2024-01-02 170718](https://github.com/SubhashriRavichandran10/copy-file/assets/145743413/cc800c83-3fc4-4283-ac76-1c5a614f8470)

![Screenshot 2024-01-02 170740](https://github.com/SubhashriRavichandran10/copy-file/assets/145743413/a48c28c0-6684-477b-a07c-5dda9d2de9ae)
![Screenshot 2024-01-02 170752](https://github.com/SubhashriRavichandran10/copy-file/assets/145743413/a751848b-d91f-4b63-85ff-d644a2997e62)

![Screenshot 2024-01-02 170802](https://github.com/SubhashriRavichandran10/copy-file/assets/145743413/06ad0ed2-c72a-4192-a734-d16e4e432572)




## RESULT:
Thus the program is written to copy the contents from one file to another file.
