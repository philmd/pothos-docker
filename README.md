# pothos-docker

Dockerized Pothos data-flow framework

[Pothosware](https://github.com/pothosware)

# Installation

Download:

```bash
docker pull philmd/pothos:latest
```

Run PothosUtil:

```bash
docker run philmd/pothos:latest --system-info
Lib Version: 0.4.0-ppa1~xenial
API Version: 0.4.0
ABI Version: 0.4-3
...
docker run philmd/pothos:latest --self-tests
Testing /object/tests/test_object_equals... success!
Testing /object/tests/test_object_value... success!
Testing /object/tests/test_object_throw... success!
...
```

Build the image yourself:

```bash
docker build -t philmd/pothos github.com/sameersbn/docker-skype
```

With the image locally available, run the wrapper scripts using:

```bash
./pothos-gui-wrapper
```

This will launch `PothosGui`.
