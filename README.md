# Haskell Buildpack Demo


It uses the yaaS Haskell Buildpack:

https://github.com/georgkreimer/yaas-buildpack-haskell

## Pushing to yaaS

Clone this repository:

    git clone https://github.com/georgkreimer/haskell-buildpack-demo.git

Adjust the manifest.yml

Push!

    cf push <app-name> -f manifest.yml

*Note*: the push will take some time to install dependencies and might
not show any output for quite a while. It will also show a lot of
warnings.
