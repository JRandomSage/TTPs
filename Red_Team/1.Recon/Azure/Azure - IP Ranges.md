# Azure - IP Ranges

```download=$(curl -s https://www.microsoft.com/en-us/download/confirmation.aspx?id=41653 | grep '{base_0:{url:"' | cut -d ':' -f3,4 | cut -d '"' -f2) && curl -s $download | cut -d '"' -f2 | grep [0-9] | grep -v [a-zA-Z]```

Bash one liner to grab current Azure IP ranges
