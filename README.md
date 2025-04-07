# Metasploit-for-reconnaissance
# Metasploit
Metasploit for reconnaissance in pentesting

# AIM:

To get introduced to Metasploit Framework and to  perform reconnaissance  in pentesting .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

### Step1:Identify the Attacker’s IP Address
Determine the IP address of the attacker's system.

![image](https://github.com/user-attachments/assets/04be3933-bd4c-4695-8901-0e0cf7c34fd4)

### Step2:Launch the Metasploit Console
Invoke the **msfconsole**.

![image](https://github.com/user-attachments/assets/a22a6421-acdf-4728-811e-ec60ed582f15)


To view available commands, enter **"?"**.
![image](https://github.com/user-attachments/assets/9898388a-1dd5-4eb6-9501-135fa8364205)


### Step3:Generate Payload Using msfvenom

Execute the following command to generate a Windows Meterpreter reverse shell payload.
![Screenshot 2025-04-07 104941](https://github.com/user-attachments/assets/861d30bd-b939-429d-a907-19e23102afdf)

### Step4:Set Up an HTTP Server
Once the payload file is created, navigate to the home directory.
Right-click and select **"open terminal here"**.
![Screenshot 2025-04-07 105255](https://github.com/user-attachments/assets/e3c700fe-099d-49d1-9e25-be911d70c7b0)


Run the Python command to establish an HTTP server for file distribution.
![image](https://github.com/user-attachments/assets/a9a1cd2d-c4fe-4d3f-9a33-50aca4b6a891)

### Step5:Distribute the Payload
Share the .exe file with the target system via any medium or the HTTP server.

Once the victim downloads and executes the file, the exploit is triggered.

**VICTIM DEVICE:**
![Screenshot 2025-04-07 104310](https://github.com/user-attachments/assets/680c8dbd-88d6-4bf5-aad3-dff3709d043b)

![Screenshot 2025-04-07 104543](https://github.com/user-attachments/assets/6d62c76b-306b-484a-a0d6-f7c346abdccf)

### Step6:Establish a Connection
On Kali Linux, reopen the terminal and invoke **"msfconsole"**.
Follow the necessary steps to establish a connection with the victim’s device.

![Screenshot 2025-04-07 105551](https://github.com/user-attachments/assets/a75f56d6-544d-45bf-a02b-e419bbabe5f3)

Once exploited, a session is created, allowing remote access without the victim’s awareness.

### Step7:List commands
Use the help command to list available operations.
![Screenshot 2025-04-07 105946](https://github.com/user-attachments/assets/285cc91c-fece-4b4d-afcd-b0b22391bf09)


### Step8:
For example, the **"screenshot"** command captures the victim’s screen and saves it in the attacker's home directory.

![Screenshot 2025-04-07 105551](https://github.com/user-attachments/assets/d8774d47-edc4-4a2f-8735-1bb80bf67873)

![WhatsApp Image 2025-04-07 at 11 03 10_cd03e798](https://github.com/user-attachments/assets/b2bd93b8-20cc-4105-8bda-09e37e51533c)


### Step9:Terminate the Connection
After completing the intended operations, close the session securely.

#### RESULT:
The Metasploit framework for reconnaissance is  examined successfully.
