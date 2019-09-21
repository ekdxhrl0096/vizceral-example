![](https://raw.githubusercontent.com/Netflix/vizceral/master/logo.png)

##### Using Docker
If you don't have a node environment setup or would like to run this example on a platform, there is a Dockerfile for experimental usage.

```
$ docker build -t message-platform/topology . ; docker stop message-platform/topology; docker run --rm --name message-platform-topology -p 41911:8080 -d message-platform/topology
$ open http://localhost:41911/message-platform
```

Then you should be able to navigate to http://localhost:41911/message-platform
