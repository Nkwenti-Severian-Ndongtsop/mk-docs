# This is a brief documentation on docker
We started by launching an instance called docker using the command 
```sh
multipass launch docker
```
This command launches docker on your terminal.

The next thing we did was creating a virtual machine using the command 

```sh
multipass launch doker --name dockervm
```

The dockervm represents the name of the virtual machine in the docker instance*

We also learnt how to list virtual machines present on the instance using this command 

```sh
multipass list
```

This command displays all the virtual machines avilable in the multipass. 

We also linked our host with our docker virtual machine using the command 

```sh
multipass exec docker-vm --dockerps
```

The **exec** means execute, the docker-vm represents the name of your virtual machine. The **ps** means process state.
The next we did was creating aliases. We did this by going to the shell configuration and adding aliase.
The alias we created was for the command **multi pass exec docker-vm --docker** we replaced it with **docker**. So the new command is now **dockerps** with docker acting as a kind of "variable" .
We also talked about a **Portainer** which is the graphical representation of the instance docker as on the terminal. But as a an upcoming Linix Professional we were told not to use the graphical Interface. 
