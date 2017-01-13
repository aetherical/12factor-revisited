##  III. Config (Ops)
----

### Store Config in the Environment
#### *Slightly* More Fuzzy for Ops

* Strict separation of config from code. 
* Config varies across deploys, code _does not_. 
* Doesn't include service config files such as `haproxy.cfg`.
* Don't check config into code repository. 


note:
    This one is perhaps a bit contentious.

	Avoids situations where code isn't same across environments

	
