# Tico - A Simple Version Control System
Tico is a minimalistic version control system written in Python. It provides basic versioning functionalities to help you manage changes to your project.

Installation
Clone the Tico repository to your local machine:
```bash
git clone https://github.com/MSTC-x-IITGN/WoC_6.0_Systems_Programming.git
```
Navigate to the Tico directory:
```bash
cd tico
```
Make the Tico script executable:
```bash
chmod +x tico.py
```
Copy the Tico script to a directory in your system's PATH (e.g., /usr/local/bin on Linux):
```bash
sudo cp tico.py /bin
```
Getting Started
Follow the steps below to initialize and use Tico:

Initialize a new Tico repository:

```bash
tico init
```
Add a file to the index:

```bash
tico add <file>
```
Commit changes with a message:

```bash
tico commit -m <message>
```
Remove a file from the index:

```bash
tico rmadd <file>
```
Remove the last commit:

```bash
tico rmcommit
```
Display commit log:

```bash
tico log
```
Checkout a specific commit:

```bash
tico checkout <commit>
```
See usage help:

```bash
tico help
```
See the repository status:

```bash
tico status
```
See the present user (default username is naveen):

```bash
tico user show
```
Change the user:

```bash
tico user set <username>
```
Push your files to another folder:

```bash
tico push <path>
```
# Tutorial
Watch this tutorial to get started with Tico.
<br>
[![Tutorial](tutorial)](https://www.youtube.com/watch?v=A4JXYHFW7FM)

# Setting Up Python File
# Windows
Save the Tico script as tico.py.

Add the folder containing tico.py to your system's PATH.

Open Command Prompt and use Tico commands.

# Mac and Linux
Save the Tico script as tico.py.

Make it executable and Move it to a directory in your system's PATH (e.g., /usr/local/bin):


```bash
chmod +x tico.py
sudo cp tico.py /usr/local/bin/tico
```

Open Terminal and use Tico commands.
