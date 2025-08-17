<#
.SYNOPSIS
Windows 10 account lockout duration must be configured to 15 minutes or greater.
.NOTES
    Author          : Jaime Roque 
    LinkedIn        : linkedin.com/in/jars25
    GitHub          : github.com/jars25
    Date Created    : 2025-16-08
    Last Modified   : 2025-16-08
    Version         : 1.0
    CVEs            : N/A
    Plugin IDs      : N/A
    STIG-ID         : WN10-AC-000005

.TESTED ON
    Date(s) Tested  : 
    Tested By       : 
    Systems Tested  : 
    PowerShell Ver. : 

.USAGE
    Put any usage instructions here.
    Example syntax:
    PS C:\Users\jars\Desktop> C:\Users\jars\Desktop\WN10-AC-000005.ps1
#>

# Choose ONE value:
$minutes = 15     # compliant (≥15)
# $minutes = 0    # also compliant (requires admin to unlock)

# Set lockout duration (minutes)
& net accounts /lockoutduration:$minutes | Out-Null

# Verify
(net accounts) | Select-String 'Lockout duration'


