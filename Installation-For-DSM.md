# Installation via Scheduled Tasks

This installation method intalls and updates the _Transmission Web Control_ interface via Synology's native scheduled tasks, without the need of any experience with Linux (and the hassle to config SSH).

## Step 1: Add a Scheduled Task

- Add a new Scheduled Task on behalf of `root`. The schedule you specify here will be the schedule for DSM to check and install any future updates.
- Under _Task Settings_, paste the following command:
```
curl -s https://raw.githubusercontent.com/ronggang/transmission-web-control/master/release/install-tr-control-cn.sh | bash -s auto
```

That's it! If everything's good, _Transmission Web Control_ will be available at port 9091 after you run the task for the first time.