## bt-rep

This script downloads one crashreport from [rdkbacktrace](https://rdkbacktrace.stb.r53.xcal.tv)

Usage:
> bt-rep \<object-id\> \[ \<path-to-store-crashreport\> \]

    <object-id> is a 8-digit hexadecimal number identfying the crashreport
    The directory named <object-id> is being created in the specified path
    or in the current directory (if the path is not specified)

The script internally uses such tools as `morgue` and `jq`

Expired
