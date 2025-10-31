# Windows-basic-commands-batchscript
Ex08-Windows-basic-commands-batchscript

# AIM:
To execute Windows basic commands and batch scripting

# DESIGN STEPS:

### Step 1:

Navigate to any Windows environment installed on the system or installed inside a virtual environment like virtual box/vmware 

### Step 2:

Write the Windows commands / batch file . Save each script in a file with a .bat extension. Ensure you have the necessary permissions to perform the operations. Adapt paths as needed based on your system configuration.
### Step 3:

Execute the necessary commands/batch file for the desired output. 




# WINDOWS COMMANDS:
## Exercise 1: Basic Directory and File Operations

Create a directory named "my-folder"

<img width="861" height="101" alt="448216196-539dfc63-4b77-49fe-9606-b753d9725d96" src="https://github.com/user-attachments/assets/12cc8f55-918e-4dfe-83bd-96f6f8142f9c" />


## COMMAND AND OUTPUT
Remove the directory "my-folder"

<img width="939" height="105" alt="448216233-95d585af-52fc-47e2-bd8a-dcd2b261f2a8" src="https://github.com/user-attachments/assets/b913e072-3040-447a-93e8-9369d70d4988" />


## COMMAND AND OUTPUT

Create the file Rose.txt

<img width="976" height="65" alt="448216262-d6e93a7c-e720-4452-b709-0a8ffe2d4378" src="https://github.com/user-attachments/assets/7472e54d-13ad-4afe-8f4e-8cd2e0787c78" />



## COMMAND AND OUTPUT

Create the file hello.txt using echo and redirection


<img width="1063" height="36" alt="448216366-da1c6158-e8f8-48da-a17d-1a0842005396" src="https://github.com/user-attachments/assets/88558a52-36cc-4b99-a4af-ec18c6fa01e9" />


## COMMAND AND OUTPUT

Copy the file hello.txt into the file hello1.txt


<img width="990" height="115" alt="448216388-ecff7158-dc75-4a69-a0fb-46d22561a57d" src="https://github.com/user-attachments/assets/e00d12c8-5534-473e-87f8-e292dbc4147f" />

## COMMAND AND OUTPUT

Remove the file hello1.txt

<img width="990" height="115" alt="448216388-ecff7158-dc75-4a69-a0fb-46d22561a57d" src="https://github.com/user-attachments/assets/a112f787-e32d-42ab-aab0-c35042dbe5ab" />


## COMMAND AND OUTPUT

List out the file hello1.txt in the current directory

<img width="944" height="184" alt="448216594-07cd4642-569c-40ad-9e17-730ce944422d" src="https://github.com/user-attachments/assets/1b7c41ca-63fe-4488-86e2-4a36667c22ec" />


## COMMAND AND OUTPUT

List out all the associated file extensions 

<img width="788" height="1064" alt="448216657-45879941-6339-46a1-bbda-5f926ebb6ac5" src="https://github.com/user-attachments/assets/fbcfee10-cf9f-4c05-aa25-0de218d97a4d" />

<img width="1059" height="1089" alt="448216701-d0b35aac-67f7-4d44-8ea9-611b5cbf80b7" src="https://github.com/user-attachments/assets/cc1ad094-8723-4247-90ea-5117ea66b6f8" />

<img width="963" height="1149" alt="448217326-ea72d09e-04bc-4cfd-ba52-0556afe7a9b6" src="https://github.com/user-attachments/assets/2b76db64-8465-438b-b74d-fffedd78ec96" />

<img width="1920" height="1200" alt="448217373-87c2e3f9-8676-4d93-942c-c09b01864d10" src="https://github.com/user-attachments/assets/39b3b68a-d690-43bb-97aa-958fd4dd04de" />


<img width="1911" height="1167" alt="448217394-2f7d69b0-7b34-4cb3-9c90-a14a8c001d98" src="https://github.com/user-attachments/assets/2266beec-231e-4bba-859c-9c9105ccb67b" />

<img width="1174" height="1089" alt="448217461-cb4492ab-efca-444b-98f9-3f2434f9abe8" src="https://github.com/user-attachments/assets/8d0aef8f-4e10-4e30-ba12-25e460ae1636" />

<img width="901" height="1088" alt="448217480-d3c0f743-b9c1-4bf5-918f-684d550d16cc" src="https://github.com/user-attachments/assets/b2220f20-214b-47ae-96f2-541a38bcc4ef" />


## COMMAND AND OUTPUT


Compare the file hello.txt and rose.txt

<img width="948" height="161" alt="448217522-746498e9-5984-499b-a1c5-15e36e20ec87" src="https://github.com/user-attachments/assets/4a6eb9e7-4941-4fe2-a65c-df565cffaa01" />

## COMMAND AND OUTPUT

## Exercise 2: Advanced Batch Scripting
Create a batch file named on the desktop. The batch file need to have a variable assigned with a desired name for ex. name="John" and display as "Hello, John".





## OUTPUT


<img width="510" height="97" alt="448217600-d8f09a95-4427-40bb-9ca5-27aaea74a2f0" src="https://github.com/user-attachments/assets/5dda5d37-e35b-4347-b04f-a42f67f9674c" />

Create a batch file  on the desktop that checks whether a user-input number is odd or not. The script should:
Prompt the user to enter a number.
Calculate the remainder when the number is divided by 2.
Display whether the number is odd or not.
Ask the user if they want to check another number.
Repeat the process if the user enters Y, and exit with a thank-you message if the user enters N.
Handle invalid inputs for the continuation prompt (Y/N) gracefully.



## OUTPUT


<img width="591" height="231" alt="448217657-d860c161-43f7-405a-ad32-407fe6e58409" src="https://github.com/user-attachments/assets/0d081983-0371-4beb-9304-e549cae2c664" />


Write a batch file that uses a FOR loop to iterate over a sequence of numbers (1 to 5) and displays each number with the label Number:. The output should pause at the end.




## OUTPUT


<img width="433" height="197" alt="448217731-0ae3a3be-394b-4656-ae86-ad9b3ab3c0a1" src="https://github.com/user-attachments/assets/2dfee4f2-47ac-4508-bdfe-2946460e5e5d" />


Write a batch script to check whether a file named sample.txt exists in the current directory. If the file exists, display the message sample.txt exists. Otherwise, display sample.txt does not exist. Pause the script at the end to view the result.

Instructions:
Use the IF EXIST conditional statement.
Make sure the script works for files located in the same directory as the batch file.
Use pause to keep the command window open after displaying the message.
Expected Output (if the file exists):

## OUTPUT

<img width="412" height="62" alt="448217759-c7109c49-6e6c-4b47-bbe0-36e0b0d00aec" src="https://github.com/user-attachments/assets/9c229616-afaa-4228-9323-efbd05ddf9db" />


Write a batch script that displays a simple menu with three options:
Say Hello – Displays the message Hello, World!
Create a File – Creates a file named newfile.txt with the content This is a new file
Exit – Exits the script with a goodbye message
The script should repeatedly display the menu until the user chooses to exit. Use goto statements to handle menu navigation.


## OUTPUT

<img width="380" height="159" alt="448217778-fb5c4305-e6d5-4298-9e7b-6c8c5f3525cc" src="https://github.com/user-attachments/assets/97376135-cd80-4203-a809-b43b9e1c9e38" />

<img width="413" height="163" alt="448217802-0d3017d6-89aa-4a1f-af2f-baab006f0cfc" src="https://github.com/user-attachments/assets/028f8f3d-c1cb-49f1-993d-52d8becf2bae" />

<img width="399" height="153" alt="448217819-f6c24ca1-ef93-4e1e-8698-98d66dc64069" src="https://github.com/user-attachments/assets/199ea40e-f259-44a1-986b-a3b0b44a426d" />





# RESULT:
The commands/batch files are executed successfully.

