# Saved wifi password lookup

> Simple 10 liner python code which tells all the saved passwords in the system.  
> Password should be saved in order to fetched by the script.  

# Output

![Output](https://user-images.githubusercontent.com/40369168/164936372-7d690bdf-101b-4aae-85bf-9e2250843d37.png)


# Modules used

1. subprocess

# Need? 

> There exist a cmd command ```[for /f "skip=9 tokens=1,2 delims=:" %i in ('netsh wlan show profiles') do @echo %j | findstr -i -v echo | netsh wlan show profiles %j key=clear]``` which does the same task, but learning the whole lot of things is a difficult task for anyone.  
> In order to check such small tasks, we use scripts which'll do the tasks for us.  
> Automating the things is quite easy and it's proper time utilization too.  

# Author

[Nitin Kumar](https://linkedin.com/in/nitin30kumar)
