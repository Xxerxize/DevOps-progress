# INSTALL CHOCOLATEY 

>search for chocolatey installation on any search engine.
[chocolatey install](https://chocolatey.org/install)

>Open powershell on your machine and run as administrator

![Powershell](https://github.com/chechechek88/DevOps-progress/blob/main/screenshots/powershell.png)

>Run 
```r
   Get-ExecutionPolicy. 
 ```
 If it returns _Restricted_, 
 > then run 
 ```
     Set-ExecutionPolicy AllSigned 
```
![all assigned](https://github.com/chechechek88/DevOps-progress/blob/main/screenshots/get%20execution.png)
> Then run the command:
```r
Set-ExecutionPolicy Bypass -Scope Process -Force; [System.Net.ServicePointManager]::SecurityProtocol = [System.Net.ServicePointManager]::SecurityProtocol -bor 3072; iex ((New-Object System.Net.WebClient).DownloadString('https://community.chocolatey.org/install.ps1'))
```
