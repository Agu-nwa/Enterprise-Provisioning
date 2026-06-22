# Enterprise-Provisioning

## ⚙️ : Create User

### : Command

````bash
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

## ⚙️ : Change Ownernership

### : Command
```bash
sudo chown dimma:dimma /home/dimma

┌──(kali㉿kali)-[~]
└─$


## ⚙️ : Verify

### : Command
```bash
ls -ld /home/dimma
drwxr-xr-x 2 dimma dimma 4096 Jun 22 16:08 /home/dimma

┌──(kali㉿kali)-[~]
└─$

## ⚙️ : Set permissions


### : Command
```bash
 sudo chmod 700 /home/dimma

┌──(kali㉿kali)-[~]
└─$


## ⚙️ : Login

### : Command
```bash
su - dimma
Password:
┏━(Message from Kali developers)
┃
┃ This is a minimal installation of Kali Linux, you likely
┃ want to install supplementary tools. Learn how:
┃ ⇒ https://www.kali.org/docs/troubleshooting/common-minimum-setup/
┃
┃ This is a cloud installation of Kali Linux. Learn more about
┃ the specificities of the various cloud images:
┃ ⇒ https://www.kali.org/docs/troubleshooting/common-cloud-setup/
┃
┗━(Run: “touch ~/.hushlogin” to hide this message)
$


## ⚙️ : Verify Privileged Operations.

### : Command
```bash
 whoami
dimma
$


## ⚙️ : verify administrative access:

### : Command
```bash
sudo whoami
[sudo] password for dimma:
root
$



````
