## Overview
[`macaca-chromedriver-zxa`](https://www.npmjs.com/package/macaca-chromedriver-zxa) is a Node.js wrapper for the selenium chromedriver.

Affected versions of the package are vulnerable to Man in the Middle (MitM) attacks due to downloading resources over an insecure protocol. Without a secure connection, it is possible for an attacker to intercept this connection and alter the packages received. In serious cases, this may even lead to Remote Code Execution (RCE) on your host server.

## Remediation
There is no fix version for `macaca-chromedriver-zxa`.
