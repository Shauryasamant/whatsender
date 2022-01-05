# whatsender
WhatSender is a python package that allows you to send Whatsapp messages at a given time.


# HOW TO USE

```python
from WhatSender import SendMessage

SendMessage("+972544985275", #Number
            "Good Morning ♥", #Message
            "13:13", #Time
            spam=False, #Spammer
            download=True #Download Images
            )                 

```

# PAY ATTENTION! <3

* You only need to set download to be true on the first run of the package,<br>
  Keeping it on won't make the app crush but it will cost more of the computer resources.

* Make sure you don't use spamming with the regular SendMessage with a loop, It will make your PC crash, Trust me.<br>
  Insted just set the varibale 'spam' to be True like this: 
  
```python
from WhatSender import SendMessage

SendMessage("+972544985275", #Number
            "Good Morning ♥", #Message
            "13:13", #Time
            spam=True, #Spammer
            download=True #Download Images
            )                 

```
