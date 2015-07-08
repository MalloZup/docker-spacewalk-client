# spacewalk-client

easy way:

```
sudo -s
docker pull pajinek/spacewalk-client
sh run 10
```

build:

```
 docker build -t spacewalk-client .
```
run:

```
 docker run -i -t spacewalk-client /root/register.sh <login> <password> <server>
```

It is possible to running of registration several times simultaneously

```
 sh run.sh <number>
```
Default value for repeating is 25.
