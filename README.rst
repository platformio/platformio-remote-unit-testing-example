..  Copyright 2014-present PlatformIO <contact@platformio.org>
    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at
       http://www.apache.org/licenses/LICENSE-2.0
    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.

PlatformIO Remote Unit Testing Example
======================================
.. image:: https://travis-ci.com/ProgmaticProgrammer/platformio-remote-unit-testing-example.svg?branch=master
    :target: https://travis-ci.com/ProgmaticProgrammer/platformio-remote-unit-testing-example
    
* `Travis.CI Test Results <https://travis-ci.com/ProgmaticProgrammer/platformio-remote-unit-testing-example>`_
* `PlatformIO Unit Testing <http://docs.platformio.org/en/latest/plus/unit-testing.html>`_
* `PIO Remote™ <http://docs.platformio.org/en/latest/plus/pio-remote.html>`_

----------

* `.travis.yml <https://github.com/ProgmaticProgrammer/platformio-remote-unit-testing-example/blob/master/.travis.yml>`_ configuration file

----------

1.  Define `PLATFORMIO_AUTH_TOKEN <http://docs.platformio.org/en/latest/envvars.html#envvar-PLATFORMIO_AUTH_TOKEN>`_
    environment variable in project settings. See
    `Travis.CI: Defining Variables in Repository Settings <https://docs.travis-ci.com/user/environment-variables/#Defining-Variables-in-Repository-Settings>`_
2.  Start `PIO Remote™ Agent <http://docs.platformio.org/en/latest/plus/pio-remote.html#pioremote-agent>`_
    on a host machine where embedded devices are connected
3.  Push commit to Repository (Trigger Travis.CI).

----------

1.  Change python to 3.7
2.  Use latest platformio instead of dev
3.  Make all tests pass
4.  Use Tiva C (TM4C123GXL) as the remote embedded tests

.. image:: travis-ci-test-results.png
    :target: https://travis-ci.com/ProgmaticProgrammer/platformio-remote-unit-testing-example
