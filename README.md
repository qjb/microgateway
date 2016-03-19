# apiconnect-microgateway
The apiconnect-microgateway is the enforcement component of the apiconnect
collection of components providing solutions for API creation, deployment,
lifecycle management, monitization, and enforcement. The micro gateway is
fundamentally a proxy securing and forwarding requests to a back end API.
It was created using StrongLoop technology and a series of middleware
components. The package is customize to work with the apiconnect 
infrastructure that automatically communicates with the micro gateway to
dynamically load APIs, Products, and Plans so that APIs are secured and
processed in a seamless fashion.

# Installation
The apiconnect-microgateway is automatically downloaded and setup during
`apiconnect` installation. You do not need to manually download and install
it.

If you would like to use apiconnect-microgateway as a standalone gateway,
use `npm -i apiconnect-microgateway` to install it. To start the gateway,
use `node .`. 

## Configuration
By default, the gateway look up the configuration from `config/default`
directory. The configuration includes the APIs, Products, and Plans metadata.
You can define an alternative configuration directory via providing the
`CONFIG_DIR` environment variable.
