### POD Defination
creating an new pod yaml files:
>> nano myfirstpod.yml
 
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

>> kubectl create -f myfirstpod.yml
