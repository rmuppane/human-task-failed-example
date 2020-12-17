Error paths implementation for Human tasks
==========================================

This exmaple provides implementation about, how to create a error paths for Human task when it is failed status.

By implementating the listener we can set a process variable value in listener. Based process variable value the process will go either it's intended path or error path.

Listener was implemented [at](https://github.com/rmuppane/human-tasks-error-path.git). Checkout the listener code and build (mvn clean install). 

Copy the listener jar in kie-serve
