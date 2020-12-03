DoS tool
=============

DoS tool ported to Go language from Python. 
Original Python http://www.sectorix.com/2012/05/17/web-server-dos-tool/
I just ported the code as is quick Original functions names are keeped and original logic mostly keeped too.

This tool targeted for stress testing and may really down badly configured server or badly made app. Use it carefully.

Examples:

    $ dos -site http://example.com/test/ 2>/dev/null

    $ dos -site http://example.com 2>/tmp/errlog

Useful environment vars:

* GOMAXPROCS
  Set it to number of your CPUs or higher (no more actual for latest golang versions).
  Limit the connection pool (1024 by default).

More details: http://old.siberian.laika.name/node/7 

Update: well, I created this utility for one time task when I only played a bit with golang. Surprisingly I found that
this utility used by other people, got some stars on github and even included in [Linux distro](http://blackarch.org/dos.html). So I cleaned up code a bit.

License
=======

I think it may be public domain because of it is just simple and short piece of code but for reason I don't remember already
I have choose GPL for it. Okey. So, Go version of dos licensed under GPLv3. See LICENSE.


 

# dosattack
# dosattack
