# Distroless Demo
[Distroless](https://github.com/GoogleContainerTools/distroless) is container image built by google which is basically docker image minus operating system

## Building Image
```
docker build -t distroless-demo .
```

## Run docker
```
docker run -d -p 8080:8080 --name dsl-demo distroless-demo
```

Browse [http://localhost:8080](http://localhost:8080) from browser

---

Read my medium blog for more: [Distroless is for Security if not for Size](https://medium.com/@dwdraju/distroless-is-for-security-if-not-for-size-6eac789f695f)
