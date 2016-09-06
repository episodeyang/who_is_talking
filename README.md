# who_is_talking
A web app that tells you how often is women talking vs man

**link to repository**: [github](https://github.com/episodeyang/who_is_talking)

## Todo List
- [ ] getting audio input to work in browser might not be trivia. 
    - use either flash, or `navigator.webkitGetUserMedia` via https on Chrome.
    
- [ ] **assess the data**: 
    some of the files have different bit rate, resulting in this kind of frequency doubling artifact: 
    ![frequency doubling](training/F_anthem_03_rand_64kb.mp3.wav.png?raw=true)