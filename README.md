# PyWiW

PyWiW is a Python wrapper library for the WhenIWork API built to simplify requests to the WhenIWork platform. 

## Installation

From GitHub :

```
$ pip install git+https://github.com/bannour-stuart/PyWiW
```

## Prerequisites

* Python 3.7
* A WhenIWork account and API token. Find out how to get your account's token on https://apidocs.wheniwork.com/external/index.html#section/Authentication

## How to set up

```
from PyWiW import WiW

key = '<API_token>'

account = WiW(token = key)
# Set child account user_ID with which you'd like to interact with
account.user_id = '<W-UserID>'
```

## API Official Doc 

* [When I Work API Doc](https://apidocs.wheniwork.com/external/index.html)


