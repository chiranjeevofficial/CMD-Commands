# CMD-Commands

1. Check Saved Wifi Password
    - Show profile of wlan netrworks
        ```linux
        netsh wlan show profile
        ```

    - Write Network Profile Name in underscores
        ```linux
        netsh wlan show profile name="profile_name" key=clear
        ``` 
