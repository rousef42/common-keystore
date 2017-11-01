[![License](https://img.shields.io/badge/License-EPL%201.0-red.svg)](https://opensource.org/licenses/EPL-1.0)
[![Build Status](https://travis-ci.org/dellemc-symphony/common-keystore.svg?branch=master)](https://travis-ci.org/dellemc-symphony/common-keystore)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/db3e4766a24b485a92829709deeff3f3)](https://www.codacy.com/app/svc-pebuildrelease/common-keystore?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=dellemc-symphony/common-keystore&amp;utm_campaign=Badge_Grade)
[![Slack](http://community.codedellemc.com/badge.svg)](https://codecommunity.slack.com/messages/symphony)
[![codecov](https://codecov.io/gh/dellemc-symphony/common-keystore/branch/master/graph/badge.svg)](https://codecov.io/gh/dellemc-symphony/common-keystore)
[![Maven Central](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/common-keystore/badge.svg)](https://maven-badges.herokuapp.com/maven-central/com.dell.cpsd/common-keystore)
[![Semver](http://img.shields.io/SemVer/2.0.0.png)](http://semver.org/spec/v2.0.0.html)

## common-keystore

## Description
Use this repository to generate keystores for storing certificate chains and private keys. This repository also provides the utility class for encrypting (using the public key) and decrypting (using the private key) plain text information.

Each service must have a keystore to hold both public and private keys. The project utilizes the PKCS12 keystore which is the default keystore in Java 8. 

## Documentation
You can find additional documentation for Project Symphony at [dellemc-symphony.readthedocs.io][documentation].

## Before you begin
Verify that the following tools are installed:
 
* Apache Maven 3.0.5+
* Java Development Kit (version 8)

## Building
Run the following command to build this project:
```bash
mvn clean install
```

## Contributing
Project Symphony is a collection of services and libraries housed at [GitHub][github].
 
Contribute code and make submissions at the relevant GitHub repository level. See [our documentation][contributing] for details on how to contribute.

## Community
Reach out to us on the Slack [#symphony][slack] channel by requesting an invite at [{code}Community][codecommunity].
 
You can also join [Google Groups][googlegroups] and start a discussion.
 
[slack]: https://codecommunity.slack.com/messages/symphony
[googlegroups]: https://groups.google.com/forum/#!forum/dellemc-symphony
[codecommunity]: http://community.codedellemc.com/
[contributing]: http://dellemc-symphony.readthedocs.io/en/latest/contributingtosymphony.html
[github]: https://github.com/dellemc-symphony
[documentation]: https://dellemc-symphony.readthedocs.io/en/latest/
