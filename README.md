# WindowsCheatSheet

My list of commands that help me.  If it helps you too then that's a bonus!


## Get information about a computer using WMIC
```
wmic bios get serialnumber
wmic computersystem get model,name,manufacturer
wmic csproduct get vendor,version  
```

## Get information on logged in users using query
```
quser
quser /serve:[servername]
```


<details open>
  <summary>Powershell version</summary>
```
get-wmiobject -Class Win32_Computersystem | select Username
```
</details>


<details>
  <summary>Powershell version</summary>
```
get-wmiobject -Class Win32_Computersystem | select Username
```
</details>
