![Go-StatusMonitor Logo][logo]<br>
A simple status monitor that checks the status of servers.<br>

![GitHub](https://img.shields.io/github/license/Go-StatusMonitor/Go-StatusMonitor?style=for-the-badge)

# What it does
Go-StatusMonitor checks a list of servers and outputs the status in to a MySQL table.<br>
If any servers are down it will send a email alerting you that servers are down!<br>
It out puts into a MySQL table so you could display the status of servers in tools like Grafana.<br>

# How do I setup the MySQL table?
It's simple just make a new Table a bit like this:<br>
```
CREATE TABLE GoStatusMonitor (
Server_Name VARCHAR(200) NOT NULL,
Status VARCHAR(30) NOT NULL,
);
```

# FAQ:
#### How do I compile and use this?
Run "go build go-statusmonitor.go" after changing everything you want to change,<br>
Then run the compiled version!<br>

#### Can I use this to check the status of minecraft servers?
Yes.

#### Can I use this to check the status of my website?
Yes.

#### Can I download and use this for private / commercial use?
Yes, you can do anything you want with code / program as long as you do not remove the copyright message and/or the license.

# Contributors
#### [Joshua Sing @joshuasing](https://github.com/joshuasing)
#### [Joel Sing @4a6f656c](https://github.com/4a6f656c)

[logo]: https://raw.githubusercontent.com/Go-StatusMonitor/Go-StatusMonitor/master/logo/Go-StatusMonitor%20Logo%20Cropped.png "Go-StatusMonitor Logo"
