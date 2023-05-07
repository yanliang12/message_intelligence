# start docker instance

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
