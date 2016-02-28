## Instant Certificate Export (ICE)

_ICE allows you to easily create exports (CSV files) from the local machine certificate store, either from local or domain joined computers._

The tool will:
- List all AD computers, so that you can easily select the ones for your query
- Fetch certificates from the local machine store of the computers you selected
- Checks the expiration date and changes the output color accordingly (Red = expired)
- Enable you to export the results to a CSV

The minimal requirements are:
- Active Directory Powershell module
- Windows PowerShell version 3 or higher
- Domain joined workstation
- WinRM enabled

***

![Sample](https://github.com/ahatting/ICE/blob/master/sample.png "ICE")
