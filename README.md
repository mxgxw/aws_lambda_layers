# aws_lambda_layers
This repository contains my personal collection of AWS lambda layers for Python.

To prepare a layer open any of the folders and run:

```bash
./update_requirements.sh
./make_layer.sh
```
## Available Layers
All layers work independently of each other.
* cryptography >= 2.9.2
* pyjwt (latest stable)
* PyMySQL (latest stable)
* requests>=2.23.0
