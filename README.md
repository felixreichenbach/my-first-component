# Viam Modular Resources - Get Started

Viam has the concept of modular resources. There are two types of resources, components representing devices and services for all sorts of software services. While there are many "plug and play" resources available in the Viam registry, you still want to be able to plug your very specific hardware into your applications. This is a simple get started example using Python. Since Viam uses gRPC and Protobuf, the same concept applies to our other SDKs as well.

The sample code is sourced from [here](https://github.com/viamrobotics/viam-python-sdk/blob/main/examples/simple_module/README.md), maintained by the Viam SDK development team.

## Setup Your Environment

Create the virtual environment

```python3 -m venv .venv```

Activate the virtual environment

```source .venv/bin/activate```

Install the Viam Python SDK

```pip3 install -r requirements.txt```

