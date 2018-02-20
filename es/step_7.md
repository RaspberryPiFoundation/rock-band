## Making a singer

Let's add a singer to your band!

+ Add another two sprites to your stage: a singer and a microphone.
    
    ![screenshot](images/band-singer-mic.png)

+ Before you can make your singer sing, you need to add a sound to your sprite. Make sure that you have selected your singer, then click the Sounds tab, and click **Choose sound from library**:
    
    ![screenshot](images/band-import-sound.png)

+ If you click **Vocals** on the left-hand side, you will then be able to choose a suitable sound to add to your sprite.
    
    ![screenshot](images/band-choose-sound.png)

+ Now that the sound has been added, you can add this code to your singer:
    
    ```blocks
    when this sprite clicked
    play sound [singer1 v] until done
```

+ Click on your singer and see what happens. Does she sing?