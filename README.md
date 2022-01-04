# whatsender
WhatSender is a python package that allows you to send Whatsapp messages at a given time.


# HOW TO USE

```python
from WhatSender import SendMessage

# syntax => SendMessage(number, message, timeToSend, spam, download)

SendMessage("+15134123", "Hello World", "19:02", spam=False, download=True)
```

# PAY ATTENTION! <3

* You only need to set download to be true on the first run of the package,<br>
  Keeping it on won't make the app crush but it will cost more of the computer resources.

* Make sure you don't use spamming with the regular SendMessage with a loop, It will make your PC crash, Trust me.<br>
  Insted just set the varibale 'spam' to be True like this: 
  
```python
from WhatSender import SendMessage

# syntax => SendMessage(number, message, timeToSend, spam, download)

SendMessage("+15134123", "Hello World", "19:02", spam=True, download=True)
```
