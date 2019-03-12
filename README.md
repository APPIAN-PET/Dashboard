# Dashboard

APPIAN provides a graphical-user interface via a web browser to allow you to visualize your results. This interface is called a dashboard and does not require you to install any software. 

To run the dashboard simply use :

```
    python2 APPIAN/LaunchDashboard.py -o </path/to/APPIAN/results>
```
For example, if you ran APPIAN with the following command :

```
    python2 APPIAN/Launcher.py -s /my/data/is/here -t /my/results/are/here
```

Then you would launch the dashboard by running : 

```
    python2 APPIAN/LaunchDashboard.py -o /my/results/are/here
```

Note that you cannot run this command from inside a docker container as there is no way to open up a web-browser from inside a container. 
