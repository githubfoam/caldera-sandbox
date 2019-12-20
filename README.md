# caldera-sandbox
~~~
>vagrant up vg-caldera-79
>vagrant ssh vg-caldera-79

[vagrant@vg-caldera-79 caldera]$  whoami
vagrant
[vagrant@vg-caldera-79 caldera]$ source python36/calderaenv/bin/activate

(calderaenv) [vagrant@vg-caldera-79 caldera]$ cd /home/vagrant/python36/calderaenv/caldera
(calderaenv) [vagrant@vg-caldera-79 caldera]$ python server.py &
[1] 17893
(calderaenv) [vagrant@vg-caldera-79 caldera]$ DEBUG:root:Agents will be considered untrusted after 60 seconds of silence
DEBUG:root:Uploaded files will be put in /tmp
DEBUG:root:Serving at http://0.0.0.0:8888
DEBUG:asyncio:Using selector: EpollSelector
DEBUG:data_svc:There are 0 jobs in the scheduler
DEBUG:app_svc:Enabling sandcat plugin
DEBUG:data_svc:Loading data from: plugins/stockpile/data
DEBUG:contact_svc:Started HTTP command and control channel
DEBUG:contact_svc:GIST command and control channel not started
DEBUG:app_svc:Enabling stockpile plugin
DEBUG:data_svc:Loading data from: data
All systems ready. Navigate to http://0.0.0.0:8888 to log in.

(calderaenv) [vagrant@vg-caldera-79 caldera]$

browse - google chrome
<http://192.168.18.79:8888/>
u/p admin/admin

<https://github.com/mitre/caldera>
~~~
