# message intelligence platform

```
One who listed his title as “data science team lead” said he had created a “message intelligence platform” that reads billions of messages to answer four questions: “who you are, what you do, how do you think, and what is your relationship with others.”

“With the answers to these four questions, we know everything about one person,”
```

# start docker instance

open a command prompt and copy and paste the following command

```bash
docker run -it ^
-p 0.0.0.0:3677:3677 ^
-p 0.0.0.0:3749:3749 ^
-p 0.0.0.0:3117:3117 ^
jingyanwang1/message_intelligence:2.0.5 
```

<img src="service.png" width="800" title="service">


# input interface: 

http://localhost:3117

<img src="input.png" width="800" title="input messages">


# output interface: 

http://localhost:3749/

<img src="output.png" width="800" title="outpug graph">
