## SynapsePayRest-PHP

Simple API wrapper for SynapsePay v3 REST API.

## Code Example

Check out [samples.md](samples.md) and our [API documentation](https://docs.synapsefi.com/) for examples.


## Clone the repo from GitHub
### Prerequisites
Installing git, refer to composer docs, [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

### Project Setup
Clone SynapseFI/PHP-Wrapper git repository
```
git clone https://github.com/SynapseFI/PHP-Wrapper.git
```

### Running the repository
Add this statement at the top of your source code file
```
include 'synapse_rest/client.php';
```

## Using Composer

### Prerequisites
Installing composer, refer to composer docs, [git](https://getcomposer.org/doc/00-intro.md)

### Project Setup
Create composer.json
```
{
    "require": {
        "synapsefi/synapse_pay_rest": "^2.0"
    }
}
```

### Install Dependencies
```
php composer.phar install
```

### Running the PHP-API Wrapper
Add this statement at the top of your source code file
```
require_once 'vendor/synapsefi/synapse_pay_rest/synapse_rest/client.php';

```

## License

The MIT License (MIT)

Copyright (c) 2017 Synapse Financial Technologies Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
