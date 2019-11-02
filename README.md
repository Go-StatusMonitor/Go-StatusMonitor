![Go-StatusMonitor Logo][logo]<br>
A simple status monitor that checks the status of servers.<br>

![GitHub](https://img.shields.io/github/license/Go-StatusMonitor/Go-StatusMonitor?color=blue&style=for-the-badge) ![Go Version](https://img.shields.io/badge/Go%20Version-1.13.1-blue?style=for-the-badge&logo=go) ![GitHub repo size](https://img.shields.io/github/repo-size/Go-StatusMonitor/Go-StatusMonitor?logo=github&style=for-the-badge) ![GitHub issues](https://img.shields.io/github/issues-raw/Go-StatusMonitor/Go-StatusMonitor?color=blue&logo=github&style=for-the-badge) ![GitHub forks](https://img.shields.io/github/forks/Go-StatusMonitor/Go-StatusMonitor?logo=github&style=for-the-badge) ![GitHub release (latest by date)](https://img.shields.io/github/v/release/Go-StatusMonitor/Go-StatusMonitor?style=for-the-badge)
<br><br>
# What it does
Go-StatusMonitor checks a list of servers and outputs the status in to a MySQL table.<br>
If any servers are down it will send a email alerting you that servers are down! (Can be disabled!)<br>
It outputs into a MySQL table so you could display the status of servers in tools like Grafana.<br>
<br><br>
# How do I setup the MySQL table?
It's simple just make a new MySQL Table a bit like this:<br>
```sql
CREATE TABLE GoStatusMonitor (
Server_Name VARCHAR(200) NOT NULL,
Status VARCHAR(30) NOT NULL,
);
```
<br><br>
## FAQ:
#### How do I compile and use this?
Run "go build go-statusmonitor.go" after changing everything you want to change,<br>
Then run the compiled version!<br>
<br>
#### Can I use this to check the status of minecraft servers?
Yes.
<br>
#### Can I use this to check the status of my website?
Yes.
<br>
#### Can I download and use this for private / commercial use?
Yes, you can do anything you want with code / program as long as you do not remove/edit the copyright message and/or the license.
<br>
#### Can I use the logo?
Yes, you can use it if you do not claim it as your own.
<br><br>
# Contributors
#### [Joshua Sing @joshuasing](https://github.com/joshuasing)
#### [Joel Sing @4a6f656c](https://github.com/4a6f656c)

<details>
  <summary>Go-StatusMonitor's License</summary>
BSD 2-Clause License<br>
<br>
Copyright (c) 2019, Joshua Sing<br>
All rights reserved.<br>
<br>
Redistribution and use in source and binary forms, with or without<br>
modification, are permitted provided that the following conditions are met:<br>
<br>
1. Redistributions of source code must retain the above copyright notice, this<br>
   list of conditions and the following disclaimer.<br>
<br>
2. Redistributions in binary form must reproduce the above copyright notice,<br>
   this list of conditions and the following disclaimer in the documentation<br>
   and/or other materials provided with the distribution.<br>
<br>
THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS "AS IS"<br>
AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT LIMITED TO, THE<br>
IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS FOR A PARTICULAR PURPOSE ARE<br>
DISCLAIMED. IN NO EVENT SHALL THE COPYRIGHT HOLDER OR CONTRIBUTORS BE LIABLE<br>
FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL<br>
DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR<br>
SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER<br>
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY,<br>
OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE<br>
OF THIS SOFTWARE, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE.<br>

</details>
<br>

# Created and Maintained by:
<p align="center">
	<a href="#"><img src="https://cdn.jjcemc.net/image/JoshuaLovesCode%20Logo.png"></a>
  <br>
  <a href="https://www.spigotmc.org/members/joshualovescode.600435/">Spigot</a> <a href="https://twitter.com/JoshuaLovesCode">Twitter</a> <a href="https://github.com/joshuasing">GitHub</a>
</p>

[logo]: https://raw.githubusercontent.com/Go-StatusMonitor/Go-StatusMonitor/master/logo/Go-StatusMonitor%20Logo%20Cropped.png "Go-StatusMonitor Logo"
