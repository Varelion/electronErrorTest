# electronErrorTest
## What is This?
This is created to go alongside an error report to the electron repository. It follows on the heels of [ISSUE #37156](https://github.com/electron/electron/issues/37156), where users were getting the error:

```
> my-electron-app@1.0.0 start
> electron .


[20132:0428/112812.950:ERROR:device_event_log_impl.cc(202)] [11:28:12.950] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
[20132:0428/112813.029:ERROR:device_event_log_impl.cc(202)] [11:28:13.029] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
[20132:0428/112813.293:ERROR:device_event_log_impl.cc(202)] [11:28:13.293] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
```

## Steps to reproduce
1. Download Repo.
2. CD into the root dir.
3. enter 'npm run start' into the terminal.
4. Observe error log.

```PS C:\Users\[...]\electronErrorTest> npm run start
> my-electron-app@1.0.0 start
> electron .


[20132:0428/112812.950:ERROR:device_event_log_impl.cc(202)] [11:28:12.950] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
[20132:0428/112813.029:ERROR:device_event_log_impl.cc(202)] [11:28:13.029] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
[20132:0428/112813.293:ERROR:device_event_log_impl.cc(202)] [11:28:13.293] Display:
display_layout.cc:556 PlacementList must be sorted by first 8 bits of display_id
```
