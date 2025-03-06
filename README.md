# Virtual-Privat-Networks
![image](https://github.com/user-attachments/assets/792573cf-2895-42d3-a03a-972f6c65804f)

The necessary prerequisites and installation process for using a VPN.

# VPN - Prerequisites and Installation

This tutorial outlines the prerequisites and installation ousing a VPN.
Environments and Technologies Used

A VPN (Proton VPN)
Microsoft Azure (Virtual Machines/Compute)
Remote Desktop
Internet Information Services (IIS)
Operating Systems Used

Windows 10 (21H2)
STEPS INCLUDED

STEP 1 - Locate Local IP
STEP 2 - Setting Up VM Using Azure
STEP 3 - Locating IP Through VM (France)
STEP 4 - Connecting to VPN Through VM
STEP 5 - Locating IP Through VPN (Japan)

# Installation Steps

STEP 1 - Locate your own personal IP address by going to "www.whatismyipaddress.com" which will be able to show you your local IP address. We will use this later as well. See EXAMPLE 1A below.

EXAMPLE 1A

![image](https://github.com/user-attachments/assets/81bcac97-a785-4905-90e8-fea75373af9d)

Next we will set up a virtual machine on Azure.

STEP 2 - Go to www.portal.azure.com and find Virtual Machines. (Create a free account with $200 if you need to). See Example 2A looking at the Virtual Machine set up page.

EXAMPLE 2A

![image](https://github.com/user-attachments/assets/bfcdf3d1-79eb-4868-a041-d4ca7bfc5417)

Creating the Virtual Machine on Example 2B the VM as “VM-FranceCentral” and select that for the REGION as well. Ensure the other items are selected as shown in EXAMPLE 2B & 2C.

EXAMPLE 2B

![image](https://github.com/user-attachments/assets/e51fafd0-26f4-474e-8de3-06c6723cf1a0)

For the Username and Password you can create your custom information, just record it personally.

EXAMPLE 2C

![image](https://github.com/user-attachments/assets/536b587d-8f69-4157-92ea-dd9845f1be7d)

Select the “Networking” tab towards the top of the page and view EXAMPLE 2D inputs to match.

EXAMPLE 2D

![image](https://github.com/user-attachments/assets/de2d55ec-cb11-4e02-8ca1-2ac298adba61)

Then select “Review and Create”, once it passes validation select “Create” at the bottom.

NEXT: At the Virtual Machine we find that the IP to the Virtual Machine is “20.216.176.18”. See EXAMPLE 2E

EXAMPLE 2E

![image](https://github.com/user-attachments/assets/64a0c839-1b72-4301-9346-02ee7ecb753b)

STEP 3 – Log Into the VM and Find IP Address

Now that we have set up the Virtual Machine we will connecting to it using the application “Remote Desktop Connection” (EXAMPLE 3A) and input the IP address for the VM that we located in EXAMPLE 2E and then input the set credentials we set when creating the VM (see EXAMPLE 3B). Once logged in, we will open the web browser and again look up www.whatismyipaddress.com (EXAMPLE 3C).

EXAMPLE 3A

![image](https://github.com/user-attachments/assets/f1789db6-8085-4af8-bdf2-e840a1a211ab)

EXAMPLE 3B

![image](https://github.com/user-attachments/assets/61a38075-f568-4af9-a800-1348baf57753)

When we look up the IP address for this VM through www.whatismyipaddress.com we see that this VM is showing the location for France (EXAMPLE 3C).

EXAMPLE 3C

![image](https://github.com/user-attachments/assets/f058ffee-f57f-4067-8c1f-a4eb831c52ff)

STEP 4 – CONNECTING TO VPN (Free Version)

Using the local computer go to protonvpn.com and create a free account (if you use the VM then French will display on your browser, so use local computer desktop). Once you are logged into your account, copy the URL from the Proton VPN website (EXAMPLE 4A) and then paste the URL to the VM web browser.

EXAMPLE 4A

![image](https://github.com/user-attachments/assets/8ba0e3b1-9f23-4165-a86b-a988780665f9)

Once you have logged into your Proton VPN account on the VM, you will select “Downloads” and choose to download the “Windows” version. Once the application Proton VPN is installed we will log in using the credentials we used when setting up a free account on Proton VPN. Then connect to the VPN through the installed app. See EXAMPLE 4B when this steps are completed.

EXAMPLE 4B

![image](https://github.com/user-attachments/assets/fb2c5b42-c718-4e6a-8b66-7eb3f52c7111)

On the left hand side of the VPN you can select a country where you want your VPN to be, the image below shows the VPN being connected to an IP in Japan. See EXAMPLE 4C

EXAMPLE 4C

![image](https://github.com/user-attachments/assets/59a314ca-4767-4116-9713-7b4755c41d29)

Next we will look at the IP again using the VM browser now that we have connected the VPN to Japan. The website www.whatismyipaddress.com shows yet another IP address using the VPN from Japan. This is quite amazing.

EXAMPLE 4D

![image](https://github.com/user-attachments/assets/d10d4516-2738-4bd0-8ca9-9abdf91797ba)

Looking at this exercise we see that we have utilized 3 different IP addresses just from your local computer to connect to the internet. Home IP (USA): 137.103.51.136 Virtual Machin IP (France): 20.216.176.18 Virtual Machin IP VPN (Japan) 212.102.51.251

If you no longer need the VM, ensure to remove it from the Asure account for unwanted charges.
END OF TUTORIAL


