<h1 align="center" id="heading"> My Custom Proxmox Helper </h1>

<p align="center"><sub> Always remember to use due diligence when sourcing scripts and automation tasks from third-party sites. </sub></p>

<details>
<summary markdown="span"> OS </summary>
⬇__________________________________________________________________________________________

<details>
<summary markdown="span"> Debian LXC </summary>
 
<p align="center"><img src="https://www.debian.org/Pics/debian-logo-1024x576.png" alt="Debian" height="100"/></p>

<h1 align="center" id="heading"> Debian LXC </h1>
<h3 align="center" id="heading"> Option to select version 10 or 11</h3>

To create a new Proxmox Debian (curl & sudo) LXC, run the following in the Proxmox Shell.

```yaml
bash -c "$(wget -qLO - https://github.com/ptmgcorp/proxmox/raw/main/ct/debian-v4.sh)"
```

<h3 align="center" id="heading">⚡ Default Settings:  512MiB RAM - 2GB Storage - 1vCPU ⚡</h3>

⚙️ **To Update Debian**

Run in the LXC console
```yaml
apt update && apt upgrade -y
```

____________________________________________________________________________________________ 

</details>


<details>
<summary markdown="span"> Ubuntu LXC </summary>
 
<p align="center"><img src="https://assets.ubuntu.com/v1/29985a98-ubuntu-logo32.png" alt="Ubuntu" height="100"/></p>

<h1 align="center" id="heading"> Ubuntu LXC </h1>
<h3 align="center" id="heading"> Option to select version 18.04, 20.04, 21.10 or 22.04</h3>

To create a new Proxmox Ubuntu (curl & sudo) LXC, run the following in the Proxmox Shell.

```yaml
bash -c "$(wget -qLO - https://github.com/ptmgcorp/proxmox/raw/main/ct/ubuntu-v4.sh)"
```

<h3 align="center" id="heading">⚡ Default Settings:  512MiB RAM - 2GB Storage - 1vCPU - 22.04 ⚡</h3>

⚙️ **To Update Ubuntu**

Run in the LXC console
```yaml
apt update && apt upgrade -y
```

____________________________________________________________________________________________ 

</details>
⬆__________________________________________________________________________________________
</details>
