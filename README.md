# Ransomware Attack and Protection

### This program was developed, tested and compatible for MacOS only.
## Requirements

> 1. Install Python.
> 2. Make sure to place the TestRW folder on the desktop. As we are trying to minimize the loss of valuable data, we are performing these commands on the sample files in the folder to prevent data encryption loss.
> 3. If the Ransoware.bin is not executable then run the command  "Chmod +x Ransomware" to enable the execution.


##  Ransomware Attack

> 1. The victim runs the bin file and then screen prompts to enter the email for the installation and then all the files are locked out until the ransom is paid. Upon payment, the key is delivered to the user.
> 2. The key is generated for every email and saved in our remote database.
> 3. The files are restored back to normal





## Ransomware Defence

> 1. The defender program is executed and the random file is generated. This random file is being tracked by the Defender.py application. Whenever it senses any changes being made to it, it shuts down the process that causes the changes.
> 2. Hence, any Ransomware changes to the files are observed and the process is shut down preventing the ransomware attack.
