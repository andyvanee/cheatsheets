# Screen Cheatsheet

- [Creating and Managing Screens](#creating-and-managing-screens)
- [Within a session](#within-a-session)
- [Window Management](#window-management)

## Creating and Managing Screens

```bash
# Create a named session
screen -S mysession

# Attach to running session
screen -r mysession

# List running session
screen -ls

# Start a detached session with command
screen -mdS <name>    <command>
screen -mdS mysession sudo tail -f /var/log/auth.log
```

## Within a session

    C-a d : Detach

## Window Management

I don't screen windows but <http://aperiodic.net/screen/quick_reference> is a
good reference.
