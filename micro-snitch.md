# Micro Snitch

## Description
Micro Snitch is a macOS utility that monitors and alerts you about microphone and camera usage.

## How it's used in security matters
Micro Snitch helps protect your privacy by notifying you whenever any application activates your computer's microphone or camera.

## Command syntax
Micro Snitch operates primarily through its GUI and doesn't have a command-line interface. However, you can use system commands to check for processes accessing the microphone or camera.

## Example
To check for processes accessing the microphone:

```
ps aux | grep -i "coreaudio[a-z]"
```

This command lists processes that might be accessing the microphone. Note that this is not a feature of Micro Snitch itself, but a general system command that can help achieve a similar goal.
