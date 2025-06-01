# QB64 Hidden Song Player
By - Aaditya Parashar  
Version - 1.4.4  

Features -  
1. Upto 25 Playlists with upto 100 Songs each  
2. Simple UI:  
    Playlist Tabs  
    Songs List  
    Seek Bar  
    Can be Hidden  
    Custom Font (Cannot be changed by user)  
3. When App is in focus:  
    Space - Pauses or Plays Song  
4. Mouse:  
    Seek Bar  
    PlayList Control with NEW Hover Support  
    SongList Control with NEW Scroll Support  
    Volume Control  
5. Keyboard: (Keys { 0-9, +,-, *, /, . } only on Keypad with NumLock On}  
    App Controls:   
        To Hide App: H  
        To Show App: LCtrl LShift `  
        Song Navigation with Arrow Keys  
    Song Controls:  
        Play: 0 2  
        Pause: 2  
        Restart: 0 1  
        Stop: 0 3  
        Jump 5 Seconds Backward: 0 2 4  
        Jump 5 Seconds Forward: 0 2 5  
        Set Repetition Point A: 0 \[  
        Set Repetition Point B: 0 \]  
        ReSet Repetition Points: 1 6  
        Reset Song Played Count: 0 Delete  
    Volume Controls:  
        Increase Volume by 1%: 0 +  
        Decrease Volume by 1%: 0 -  
        Increase Volume by 5%: 1 +  
        Decrease Volume by 5%: 1 -  
        Increase Volume by 50%: 3 +  
        Decrease Volume by 50%: 3 -  
        Increase Volume to 200% of Current Volume: 6 +  
        Decrease Volume to 50% of Current Volume: 6 -  
        Set Default Volume to PlayList's Current Volume: 0 *  
        Toggle Dynamic Volume: 0 /  
    Playlist Controls:  
        First Song: 0 Home  
        Last Song: 0 End  
        Previous Song: 0 4  
        Next Song: 0 5  
        Toggle Repeation: 0 6  
        Change Volume to Songs Specific: 0 7  
        Reload Song and Set Volume to 100%: 0 8  
        Exit Program: 9 or Esc when in focus  
        Reload Program: 0 9  
