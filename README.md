# Running the Examples

## Creating a virtualenv

If you do not yet have a `virtualenv` to run the examples with, you can do something like:

```shell
git clone git@github.com:dothanhlam/crossbario-autobahn-examples.git
cd ./crossbario-autobahn-examples/
virtualenv venv-autobahn
source venv-autobahn/bin/activate
pip install crossbar
```
## Starting Crossbar
```shell
cd router
crossbar start
```

## Running example
Open new terminal

```shell
python calculator/calculator.py
```
Then browsing to localhost:8080/calculator to check the result
