spark-ping
==========

A ping 'GUI' for the command line using sparklines.

Example:

    $ ./spark-ping google.com
    ▃▇▄▄▅▄▃▃▃▄▃▃▄▄▄▄▅▄▅▃▅▃▃▃▄▄▃▃▄▅▄▃▄▃ 24.731 ms

Implemented as a Ruby wrapper around your system's normal `ping` utility. 
Does not require any special gems, so it should work out of the box on
many platforms.

The sparklines are multi-byte UTF8 characters, so your terminal may or may
not display them correctly.

Tested with
-----------

- Ruby:     1.8.7, 1.9.2, 1.8.5 (centos5)
- Terminal: Terminal.app, iTerm2.app
- OS Ping:  OSX 10.7, Linux (centos5)

Install
-------

Copy it somewhere in your path. Run it like you would run `ping`.

Thanks
------

- https://github.com/holman/spark - for "sparking" this whole thing
- R.I.Pienaar (http://www.devco.net) - for the ping idea on ##infra-talk

LICENSE
-------

    Author:: Joe Miller (http://joemiller.me)
    Copyright:: Copyright (c) 2011 Joe Miller
    License:: Apache License, Version 2.0

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.