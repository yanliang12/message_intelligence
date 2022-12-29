# win

```bash
start docker run -it ^
-p 0.0.0.0:6788:6788 ^
-p 0.0.0.0:3749:3749 ^
-p 0.0.0.0:6894:6894 ^
jingyanwang1/message_intelligence:2.0.2
```

input interface: http://localhost:6894/

output interface: http://localhost:3749/browser/


# aws

```bash
docker run -it \
-p 0.0.0.0:6788:6788 \
-p 0.0.0.0:3749:3749 \
-p 0.0.0.0:6894:6894 \
jingyanwang1/message_intelligence:2.0.2 &
```

input: http://54.208.212.30:6894/ 

output: http://54.208.212.30:3749/browser/


# gcp

```bash
docker run -it \
-p 0.0.0.0:3547:6788 \
-p 0.0.0.0:3749:3749 \
-p 0.0.0.0:6894:6894 \
jingyanwang1/message_intelligence:2.0.2 &
```

input: http://34.66.57.96:3067/

output: http://34.66.57.96:3749/browser/
