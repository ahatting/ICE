## Instant Certificate Export (ICE)

_ICE allows you to easily create exports (CSV files) from the local machine certificate store, either from local or domain joined computers._

The tool will:
- List all AD computers, so that you can easily select the ones for your query
- Fetch certificates from the local machine store of the computers you selected
- Check the expiration date and change the output color accordingly
- Export the results to a CSV if you choose to

The minimal requirements are:
- Windows PowerShell version 3 or higher
- Domain joined workstation
- WinRM enabled

***

![Sample](https://github.com/ahatting/ICE/blob/master/sample1.png "ICE")
