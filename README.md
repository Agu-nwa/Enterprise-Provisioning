# Enterprise-Provisioning

## ⚙️ : Create User 

### : Command
```bash
sudo useradd dimma
                                                                                                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ 

## ⚙️ : Create Password

### : Command
```bash
sudo passwd dimma 
New password: 
Retype new password: 
passwd: password updated successfully

## ⚙️ : Grant administrative privileges 

### : Command
```bash
sudo usermod -aG sudo dimma               
                                                                                                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ 

## ⚙️ : Verify

### : Command
```bash
sudo usermod -aG sudo dimma               
                                                                                                                                                                                                            
┌──(kali㉿kali)-[~]
└─$ groups dimma
dimma : dimma sudo
                                                                                                                                                                                                            
┌──(kali㉿kali)-[~]
└─$

## ⚙️ : Create ~ Directory             

### : Command
```bash
sudo mkdir -p /home/dimma
                                                                                                                                                                                                            
┌──(kali㉿kali)-[~]
└─$


