growlme
=======

Growlme is a simple command-line tool to execute a command in a subshell and notify growl of success
or failure:

    $ growlme ant clean package

Be sure to have growlnotify installed for this version to work. If you wish to use the network version
please visit [the original author's implementation](http://github.com/robey/growlme).

By default, the notification's title is "(hostname): (command)" and the message is either
"Succeeded" or "FAILED". You can change any of these on the command line (see `--help`).

Credits
-------

Most of the code is Rui Carmo's "netgrowl", included inline and edited down a bit. You can find the
original [on his web site](http://the.taoofmac.com/space/Projects/netgrowl). Greg added the CLI
wrapper and Robey generalized it into a something that executes other programs.

Zeebo removed most of the "netgrowl" code and replaced it with one line that calls growlnotify instead.

License
-------

Licensed under the Apache License, Version 2.0 (the "License"); you may not
use this file except in compliance with the License. You may obtain a copy
of the License at

  http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS, WITHOUT
WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the
License for the specific language governing permissions and limitations
under the License.

