# request-log-definitions
Public repository for 4D [Request Log][0] definitions. 

The [RequestIDs.txt][1] file is used by the [New Log Parser][2].

This information is useful when working with the [Request Logs][0] created by 4D.

The Request Log is activated with the following code:

> `SET DATABASE PARAMETER(4D Server log recording;1) //server side`   
> `SET DATABASE PARAMETER(Client Log Recording;1) //remote side`

Definitions for the Columns within the log are available [here][0].   
Definitions for the Component/Request ID is available [here][1].

[0]: http://doc.4d.com/4Dv16R4/4D/16-R4/Appendix-E-Description-of-log-files.300-3343911.en.html#3191655
[1]: https://raw.githubusercontent.com/4D/request-log-definitions/master/RequestIDs.txt
[2]: http://kb.4d.com/assetid=77880

---

Format of the [RequestIDs.txt][1] file:

    { Component : {
      RequestID : Description
      }
    }
