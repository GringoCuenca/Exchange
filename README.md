## ExchangeVersion
This script will get the cumulative update version for the specified exchange server (2013/2016/2019).
 
**BuildNumbers link:**
https://docs.microsoft.com/en-us/exchange/new-features/build-numbers-and-release-dates?view=exchserver-2019
 
*Use:*

**Get-ExchangeServer | Get-ExchangeVersion**

or

**Get-ExchangeVersion -ComputerName ExchSrv01, ExchSrv02**

*Output:*
```
ComputerName Edition    BuildNumber ProductName                                     
------------ -------    ----------- -----------                                     
ExchSrv01    Enterprise 15.1.2375.7 Exchange Server 2016 Cumulative Update 22 (CU22) 
ExchSrv02    Enterprise 15.1.2375.7 Exchange Server 2016 Cumulative Update 22 (CU22)
```
