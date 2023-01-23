### POD Defination
```
Kind: Pod
apiVerion: v1
metadata:
  name: myfirstpod
spec:
  containers:
  - name: continer1
    image: asadzoot/helloworld
    
    ports:
    - containerPort: 80
```
