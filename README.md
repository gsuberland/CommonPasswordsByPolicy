# Common Passwords By Complexity Policy

This repository contains password lists that each conform to a specific complexity policy. These are useful for banning common passwords when users try to set them, and may also be useful as pre-filtered wordlists for password cracking.

The policies are defined as:

- **Alphanumeric** - Contains at least one lowercase or uppercase character, plus at least one digit.
- **Mixed Alphanumeric** - Contains at least one lowercase and uppercase character, plus at least one digit.
- **No Symbols** - Password consists only of a-z, A-Z, 0-9
- **Class Count** - Password contains at least N different types of character. The four classes of character are a-z, A-Z, 0-9, and any other character (e.g. symbols).

Class count policies are things like "must contain at least two types of character from the following list: lowercase, uppercase, number, symbols".

A class count policy with a minimum count of 1 is the same as having no complexity policy at all.

## From the SecLists Top 1M list

These password lists were extracted from the [SecLists Top 1000000 Common Passwords](https://github.com/danielmiessler/SecLists/tree/master/Passwords/Common-Credentials) list.

The passwords in these lists are ordered by descending commonality.

| Filename                                                     | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------------------------------------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [from-top-1M/pwlist_an_len10.txt](from-top-1M/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                         | 68717          |
| [from-top-1M/pwlist_an_len11.txt](from-top-1M/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                         | 40370          |
| [from-top-1M/pwlist_an_len12.txt](from-top-1M/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                         | 27387          |
| [from-top-1M/pwlist_an_len13.txt](from-top-1M/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                         | 17796          |
| [from-top-1M/pwlist_an_len14.txt](from-top-1M/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                         | 9548           |
| [from-top-1M/pwlist_an_len15.txt](from-top-1M/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                         | 5800           |
| [from-top-1M/pwlist_an_len16.txt](from-top-1M/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                         | 3385           |
| [from-top-1M/pwlist_an_len17.txt](from-top-1M/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                         | 1699           |
| [from-top-1M/pwlist_an_len18.txt](from-top-1M/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                         | 1179           |
| [from-top-1M/pwlist_an_len19.txt](from-top-1M/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                         | 801            |
| [from-top-1M/pwlist_an_len20.txt](from-top-1M/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                         | 552            |
| [from-top-1M/pwlist_anm_len10.txt](from-top-1M/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                         | 16884          |
| [from-top-1M/pwlist_anm_len11.txt](from-top-1M/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                         | 11029          |
| [from-top-1M/pwlist_anm_len12.txt](from-top-1M/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                         | 9200           |
| [from-top-1M/pwlist_anm_len13.txt](from-top-1M/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                         | 6898           |
| [from-top-1M/pwlist_anm_len14.txt](from-top-1M/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                         | 1789           |
| [from-top-1M/pwlist_anm_len15.txt](from-top-1M/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                         | 1003           |
| [from-top-1M/pwlist_anm_len16.txt](from-top-1M/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                         | 675            |
| [from-top-1M/pwlist_anm_len17.txt](from-top-1M/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                         | 285            |
| [from-top-1M/pwlist_anm_len18.txt](from-top-1M/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                         | 222            |
| [from-top-1M/pwlist_anm_len19.txt](from-top-1M/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                         | 170            |
| [from-top-1M/pwlist_anm_len20.txt](from-top-1M/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                         | 127            |
| [from-top-1M/pwlist_ns_len10.txt](from-top-1M/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                         | 108155         |
| [from-top-1M/pwlist_ns_len11.txt](from-top-1M/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                         | 62302          |
| [from-top-1M/pwlist_ns_len12.txt](from-top-1M/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                         | 40507          |
| [from-top-1M/pwlist_ns_len13.txt](from-top-1M/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                         | 25231          |
| [from-top-1M/pwlist_ns_len14.txt](from-top-1M/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                         | 13387          |
| [from-top-1M/pwlist_ns_len15.txt](from-top-1M/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                         | 8217           |
| [from-top-1M/pwlist_ns_len16.txt](from-top-1M/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                         | 4762           |
| [from-top-1M/pwlist_ns_len17.txt](from-top-1M/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                         | 2459           |
| [from-top-1M/pwlist_ns_len18.txt](from-top-1M/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                         | 1682           |
| [from-top-1M/pwlist_ns_len19.txt](from-top-1M/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                         | 1089           |
| [from-top-1M/pwlist_ns_len20.txt](from-top-1M/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                         | 735            |
| [from-top-1M/pwlist_cc_len10_cls1.txt](from-top-1M/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                         | 113360         |
| [from-top-1M/pwlist_cc_len10_cls2.txt](from-top-1M/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                         | 77410          |
| [from-top-1M/pwlist_cc_len10_cls3.txt](from-top-1M/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                         | 18989          |
| [from-top-1M/pwlist_cc_len10_cls4.txt](from-top-1M/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                         | 959            |
| [from-top-1M/pwlist_cc_len11_cls1.txt](from-top-1M/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                         | 66644          |
| [from-top-1M/pwlist_cc_len11_cls2.txt](from-top-1M/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                         | 46916          |
| [from-top-1M/pwlist_cc_len11_cls3.txt](from-top-1M/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                         | 12775          |
| [from-top-1M/pwlist_cc_len11_cls4.txt](from-top-1M/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                         | 872            |
| [from-top-1M/pwlist_cc_len12_cls1.txt](from-top-1M/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                         | 44149          |
| [from-top-1M/pwlist_cc_len12_cls2.txt](from-top-1M/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                         | 32729          |
| [from-top-1M/pwlist_cc_len12_cls3.txt](from-top-1M/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                         | 10674          |
| [from-top-1M/pwlist_cc_len12_cls4.txt](from-top-1M/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                         | 702            |
| [from-top-1M/pwlist_cc_len13_cls1.txt](from-top-1M/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                         | 28257          |
| [from-top-1M/pwlist_cc_len13_cls2.txt](from-top-1M/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                         | 21861          |
| [from-top-1M/pwlist_cc_len13_cls3.txt](from-top-1M/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                         | 8142           |
| [from-top-1M/pwlist_cc_len13_cls4.txt](from-top-1M/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                         | 542            |
| [from-top-1M/pwlist_cc_len14_cls1.txt](from-top-1M/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                         | 15533          |
| [from-top-1M/pwlist_cc_len14_cls2.txt](from-top-1M/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                         | 11224          |
| [from-top-1M/pwlist_cc_len14_cls3.txt](from-top-1M/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                         | 2575           |
| [from-top-1M/pwlist_cc_len14_cls4.txt](from-top-1M/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                         | 352            |
| [from-top-1M/pwlist_cc_len15_cls1.txt](from-top-1M/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                         | 9747           |
| [from-top-1M/pwlist_cc_len15_cls2.txt](from-top-1M/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                         | 6979           |
| [from-top-1M/pwlist_cc_len15_cls3.txt](from-top-1M/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                         | 1569           |
| [from-top-1M/pwlist_cc_len15_cls4.txt](from-top-1M/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                         | 186            |
| [from-top-1M/pwlist_cc_len16_cls1.txt](from-top-1M/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                         | 5936           |
| [from-top-1M/pwlist_cc_len16_cls2.txt](from-top-1M/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                         | 4225           |
| [from-top-1M/pwlist_cc_len16_cls3.txt](from-top-1M/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                         | 1108           |
| [from-top-1M/pwlist_cc_len16_cls4.txt](from-top-1M/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                         | 157            |
| [from-top-1M/pwlist_cc_len17_cls1.txt](from-top-1M/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                         | 3171           |
| [from-top-1M/pwlist_cc_len17_cls2.txt](from-top-1M/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                         | 2207           |
| [from-top-1M/pwlist_cc_len17_cls3.txt](from-top-1M/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                         | 590            |
| [from-top-1M/pwlist_cc_len17_cls4.txt](from-top-1M/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                         | 57             |
| [from-top-1M/pwlist_cc_len18_cls1.txt](from-top-1M/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                         | 2202           |
| [from-top-1M/pwlist_cc_len18_cls2.txt](from-top-1M/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                         | 1527           |
| [from-top-1M/pwlist_cc_len18_cls3.txt](from-top-1M/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                         | 444            |
| [from-top-1M/pwlist_cc_len18_cls4.txt](from-top-1M/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                         | 45             |
| [from-top-1M/pwlist_cc_len19_cls1.txt](from-top-1M/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                         | 1495           |
| [from-top-1M/pwlist_cc_len19_cls2.txt](from-top-1M/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                         | 1060           |
| [from-top-1M/pwlist_cc_len19_cls3.txt](from-top-1M/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                         | 346            |
| [from-top-1M/pwlist_cc_len19_cls4.txt](from-top-1M/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                         | 34             |
| [from-top-1M/pwlist_cc_len20_cls1.txt](from-top-1M/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                         | 1020           |
| [from-top-1M/pwlist_cc_len20_cls2.txt](from-top-1M/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                         | 720            |
| [from-top-1M/pwlist_cc_len20_cls3.txt](from-top-1M/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                         | 252            |
| [from-top-1M/pwlist_cc_len20_cls4.txt](from-top-1M/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                         | 23             |

## From the Rockyou list

These were extracted from the well-known "rockyou.txt" password list.

Some preprocessing was performed to remove passwords that are unlikely to be re-used elsewhere, e.g. passwords that were just rockyou URLs.

The passwords in these lists are unordered.

| Filename                                                     | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------------------------------------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [from-rockyou/pwlist_an_len10.txt](from-rockyou/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                         | 2236661        |
| [from-rockyou/pwlist_an_len11.txt](from-rockyou/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                         | 1226645        |
| [from-rockyou/pwlist_an_len12.txt](from-rockyou/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                         | 798023         |
| [from-rockyou/pwlist_an_len13.txt](from-rockyou/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                         | 514488         |
| [from-rockyou/pwlist_an_len14.txt](from-rockyou/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                         | 329007         |
| [from-rockyou/pwlist_an_len15.txt](from-rockyou/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                         | 194196         |
| [from-rockyou/pwlist_an_len16.txt](from-rockyou/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                         | 109456         |
| [from-rockyou/pwlist_an_len17.txt](from-rockyou/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                         | 43226          |
| [from-rockyou/pwlist_an_len18.txt](from-rockyou/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                         | 26049          |
| [from-rockyou/pwlist_an_len19.txt](from-rockyou/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                         | 16604          |
| [from-rockyou/pwlist_an_len20.txt](from-rockyou/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                         | 10980          |
| [from-rockyou/pwlist_anm_len10.txt](from-rockyou/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                         | 150544         |
| [from-rockyou/pwlist_anm_len11.txt](from-rockyou/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                         | 87375          |
| [from-rockyou/pwlist_anm_len12.txt](from-rockyou/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                         | 57935          |
| [from-rockyou/pwlist_anm_len13.txt](from-rockyou/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                         | 37499          |
| [from-rockyou/pwlist_anm_len14.txt](from-rockyou/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                         | 24770          |
| [from-rockyou/pwlist_anm_len15.txt](from-rockyou/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                         | 15714          |
| [from-rockyou/pwlist_anm_len16.txt](from-rockyou/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                         | 9073           |
| [from-rockyou/pwlist_anm_len17.txt](from-rockyou/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                         | 3378           |
| [from-rockyou/pwlist_anm_len18.txt](from-rockyou/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                         | 2016           |
| [from-rockyou/pwlist_anm_len19.txt](from-rockyou/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                         | 1294           |
| [from-rockyou/pwlist_anm_len20.txt](from-rockyou/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                         | 861            |
| [from-rockyou/pwlist_ns_len10.txt](from-rockyou/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                         | 3964740        |
| [from-rockyou/pwlist_ns_len11.txt](from-rockyou/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                         | 2097309        |
| [from-rockyou/pwlist_ns_len12.txt](from-rockyou/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                         | 1318487        |
| [from-rockyou/pwlist_ns_len13.txt](from-rockyou/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                         | 829026         |
| [from-rockyou/pwlist_ns_len14.txt](from-rockyou/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                         | 513682         |
| [from-rockyou/pwlist_ns_len15.txt](from-rockyou/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                         | 302339         |
| [from-rockyou/pwlist_ns_len16.txt](from-rockyou/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                         | 169380         |
| [from-rockyou/pwlist_ns_len17.txt](from-rockyou/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                         | 76835          |
| [from-rockyou/pwlist_ns_len18.txt](from-rockyou/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                         | 48091          |
| [from-rockyou/pwlist_ns_len19.txt](from-rockyou/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                         | 30489          |
| [from-rockyou/pwlist_ns_len20.txt](from-rockyou/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                         | 20109          |
| [from-rockyou/pwlist_cc_len10_cls1.txt](from-rockyou/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                         | 4418859        |
| [from-rockyou/pwlist_cc_len10_cls2.txt](from-rockyou/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                         | 2484937        |
| [from-rockyou/pwlist_cc_len10_cls3.txt](from-rockyou/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                         | 396005         |
| [from-rockyou/pwlist_cc_len10_cls4.txt](from-rockyou/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                         | 24400          |
| [from-rockyou/pwlist_cc_len11_cls1.txt](from-rockyou/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                         | 2405509        |
| [from-rockyou/pwlist_cc_len11_cls2.txt](from-rockyou/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                         | 1386831        |
| [from-rockyou/pwlist_cc_len11_cls3.txt](from-rockyou/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                         | 262435         |
| [from-rockyou/pwlist_cc_len11_cls4.txt](from-rockyou/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                         | 15396          |
| [from-rockyou/pwlist_cc_len12_cls1.txt](from-rockyou/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                         | 1540650        |
| [from-rockyou/pwlist_cc_len12_cls2.txt](from-rockyou/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                         | 909214         |
| [from-rockyou/pwlist_cc_len12_cls3.txt](from-rockyou/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                         | 186551         |
| [from-rockyou/pwlist_cc_len12_cls4.txt](from-rockyou/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                         | 10923          |
| [from-rockyou/pwlist_cc_len13_cls1.txt](from-rockyou/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                         | 986182         |
| [from-rockyou/pwlist_cc_len13_cls2.txt](from-rockyou/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                         | 590492         |
| [from-rockyou/pwlist_cc_len13_cls3.txt](from-rockyou/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                         | 130013         |
| [from-rockyou/pwlist_cc_len13_cls4.txt](from-rockyou/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                         | 7517           |
| [from-rockyou/pwlist_cc_len14_cls1.txt](from-rockyou/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                         | 622688         |
| [from-rockyou/pwlist_cc_len14_cls2.txt](from-rockyou/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                         | 380268         |
| [from-rockyou/pwlist_cc_len14_cls3.txt](from-rockyou/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                         | 89760          |
| [from-rockyou/pwlist_cc_len14_cls4.txt](from-rockyou/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                         | 5242           |
| [from-rockyou/pwlist_cc_len15_cls1.txt](from-rockyou/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                         | 374999         |
| [from-rockyou/pwlist_cc_len15_cls2.txt](from-rockyou/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                         | 227923         |
| [from-rockyou/pwlist_cc_len15_cls3.txt](from-rockyou/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                         | 59042          |
| [from-rockyou/pwlist_cc_len15_cls4.txt](from-rockyou/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                         | 3513           |
| [from-rockyou/pwlist_cc_len16_cls1.txt](from-rockyou/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                         | 214679         |
| [from-rockyou/pwlist_cc_len16_cls2.txt](from-rockyou/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                         | 130732         |
| [from-rockyou/pwlist_cc_len16_cls3.txt](from-rockyou/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                         | 35545          |
| [from-rockyou/pwlist_cc_len16_cls4.txt](from-rockyou/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                         | 2247           |
| [from-rockyou/pwlist_cc_len17_cls1.txt](from-rockyou/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                         | 97521          |
| [from-rockyou/pwlist_cc_len17_cls2.txt](from-rockyou/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                         | 54614          |
| [from-rockyou/pwlist_cc_len17_cls3.txt](from-rockyou/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                         | 13608          |
| [from-rockyou/pwlist_cc_len17_cls4.txt](from-rockyou/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                         | 1089           |
| [from-rockyou/pwlist_cc_len18_cls1.txt](from-rockyou/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                         | 62048          |
| [from-rockyou/pwlist_cc_len18_cls2.txt](from-rockyou/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                         | 33953          |
| [from-rockyou/pwlist_cc_len18_cls3.txt](from-rockyou/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                         | 8647           |
| [from-rockyou/pwlist_cc_len18_cls4.txt](from-rockyou/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                         | 731            |
| [from-rockyou/pwlist_cc_len19_cls1.txt](from-rockyou/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                         | 40592          |
| [from-rockyou/pwlist_cc_len19_cls2.txt](from-rockyou/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                         | 22323          |
| [from-rockyou/pwlist_cc_len19_cls3.txt](from-rockyou/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                         | 6020           |
| [from-rockyou/pwlist_cc_len19_cls4.txt](from-rockyou/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                         | 510            |
| [from-rockyou/pwlist_cc_len20_cls1.txt](from-rockyou/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                         | 27582          |
| [from-rockyou/pwlist_cc_len20_cls2.txt](from-rockyou/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                         | 15222          |
| [from-rockyou/pwlist_cc_len20_cls3.txt](from-rockyou/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                         | 4315           |
| [from-rockyou/pwlist_cc_len20_cls4.txt](from-rockyou/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                         | 370            |

## From the NCSC top 100k

These were extracted from the [NCSC top 100k password list](https://www.ncsc.gov.uk/news/most-hacked-passwords-revealed-as-uk-cyber-survey-exposes-gaps-in-online-security), published in 2019.

The passwords in these lists are ordered by descending commonality.

| Filename                                                     | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------------------------------------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [from-NCSC/pwlist_an_len10.txt](from-NCSC/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                         | 5881           |
| [from-NCSC/pwlist_an_len11.txt](from-NCSC/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                         | 1002           |
| [from-NCSC/pwlist_an_len12.txt](from-NCSC/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                         | 583            |
| [from-NCSC/pwlist_an_len13.txt](from-NCSC/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                         | 328            |
| [from-NCSC/pwlist_an_len14.txt](from-NCSC/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                         | 240            |
| [from-NCSC/pwlist_an_len15.txt](from-NCSC/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                         | 179            |
| [from-NCSC/pwlist_an_len16.txt](from-NCSC/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                         | 134            |
| [from-NCSC/pwlist_an_len17.txt](from-NCSC/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                         | 101            |
| [from-NCSC/pwlist_an_len18.txt](from-NCSC/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                         | 87             |
| [from-NCSC/pwlist_an_len19.txt](from-NCSC/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                         | 70             |
| [from-NCSC/pwlist_an_len20.txt](from-NCSC/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                         | 55             |
| [from-NCSC/pwlist_anm_len10.txt](from-NCSC/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                         | 564            |
| [from-NCSC/pwlist_anm_len11.txt](from-NCSC/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                         | 88             |
| [from-NCSC/pwlist_anm_len12.txt](from-NCSC/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                         | 54             |
| [from-NCSC/pwlist_anm_len13.txt](from-NCSC/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                         | 31             |
| [from-NCSC/pwlist_anm_len14.txt](from-NCSC/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                         | 22             |
| [from-NCSC/pwlist_anm_len15.txt](from-NCSC/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                         | 19             |
| [from-NCSC/pwlist_anm_len16.txt](from-NCSC/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                         | 12             |
| [from-NCSC/pwlist_anm_len17.txt](from-NCSC/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                         | 9              |
| [from-NCSC/pwlist_anm_len18.txt](from-NCSC/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                         | 7              |
| [from-NCSC/pwlist_anm_len19.txt](from-NCSC/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                         | 6              |
| [from-NCSC/pwlist_anm_len20.txt](from-NCSC/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                         | 6              |
| [from-NCSC/pwlist_ns_len10.txt](from-NCSC/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                         | 8720           |
| [from-NCSC/pwlist_ns_len11.txt](from-NCSC/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                         | 1811           |
| [from-NCSC/pwlist_ns_len12.txt](from-NCSC/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                         | 933            |
| [from-NCSC/pwlist_ns_len13.txt](from-NCSC/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                         | 436            |
| [from-NCSC/pwlist_ns_len14.txt](from-NCSC/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                         | 271            |
| [from-NCSC/pwlist_ns_len15.txt](from-NCSC/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                         | 186            |
| [from-NCSC/pwlist_ns_len16.txt](from-NCSC/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                         | 119            |
| [from-NCSC/pwlist_ns_len17.txt](from-NCSC/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                         | 66             |
| [from-NCSC/pwlist_ns_len18.txt](from-NCSC/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                         | 55             |
| [from-NCSC/pwlist_ns_len19.txt](from-NCSC/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                         | 41             |
| [from-NCSC/pwlist_ns_len20.txt](from-NCSC/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                         | 32             |
| [from-NCSC/pwlist_cc_len10_cls1.txt](from-NCSC/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                         | 9434           |
| [from-NCSC/pwlist_cc_len10_cls2.txt](from-NCSC/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                         | 6234           |
| [from-NCSC/pwlist_cc_len10_cls3.txt](from-NCSC/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                         | 755            |
| [from-NCSC/pwlist_cc_len10_cls4.txt](from-NCSC/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                         | 18             |
| [from-NCSC/pwlist_cc_len11_cls1.txt](from-NCSC/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                         | 2344           |
| [from-NCSC/pwlist_cc_len11_cls2.txt](from-NCSC/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                         | 1212           |
| [from-NCSC/pwlist_cc_len11_cls3.txt](from-NCSC/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                         | 230            |
| [from-NCSC/pwlist_cc_len11_cls4.txt](from-NCSC/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                         | 12             |
| [from-NCSC/pwlist_cc_len12_cls1.txt](from-NCSC/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                         | 1404           |
| [from-NCSC/pwlist_cc_len12_cls2.txt](from-NCSC/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                         | 758            |
| [from-NCSC/pwlist_cc_len12_cls3.txt](from-NCSC/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                         | 164            |
| [from-NCSC/pwlist_cc_len12_cls4.txt](from-NCSC/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                         | 10             |
| [from-NCSC/pwlist_cc_len13_cls1.txt](from-NCSC/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                         | 829            |
| [from-NCSC/pwlist_cc_len13_cls2.txt](from-NCSC/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                         | 461            |
| [from-NCSC/pwlist_cc_len13_cls3.txt](from-NCSC/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                         | 131            |
| [from-NCSC/pwlist_cc_len13_cls4.txt](from-NCSC/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                         | 6              |
| [from-NCSC/pwlist_cc_len14_cls1.txt](from-NCSC/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                         | 623            |
| [from-NCSC/pwlist_cc_len14_cls2.txt](from-NCSC/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                         | 343            |
| [from-NCSC/pwlist_cc_len14_cls3.txt](from-NCSC/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                         | 106            |
| [from-NCSC/pwlist_cc_len14_cls4.txt](from-NCSC/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                         | 6              |
| [from-NCSC/pwlist_cc_len15_cls1.txt](from-NCSC/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                         | 486            |
| [from-NCSC/pwlist_cc_len15_cls2.txt](from-NCSC/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                         | 261            |
| [from-NCSC/pwlist_cc_len15_cls3.txt](from-NCSC/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                         | 89             |
| [from-NCSC/pwlist_cc_len15_cls4.txt](from-NCSC/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                         | 6              |
| [from-NCSC/pwlist_cc_len16_cls1.txt](from-NCSC/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                         | 386            |
| [from-NCSC/pwlist_cc_len16_cls2.txt](from-NCSC/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                         | 192            |
| [from-NCSC/pwlist_cc_len16_cls3.txt](from-NCSC/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                         | 73             |
| [from-NCSC/pwlist_cc_len16_cls4.txt](from-NCSC/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                         | 6              |
| [from-NCSC/pwlist_cc_len17_cls1.txt](from-NCSC/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                         | 297            |
| [from-NCSC/pwlist_cc_len17_cls2.txt](from-NCSC/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                         | 140            |
| [from-NCSC/pwlist_cc_len17_cls3.txt](from-NCSC/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                         | 62             |
| [from-NCSC/pwlist_cc_len17_cls4.txt](from-NCSC/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                         | 6              |
| [from-NCSC/pwlist_cc_len18_cls1.txt](from-NCSC/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                         | 269            |
| [from-NCSC/pwlist_cc_len18_cls2.txt](from-NCSC/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                         | 118            |
| [from-NCSC/pwlist_cc_len18_cls3.txt](from-NCSC/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                         | 52             |
| [from-NCSC/pwlist_cc_len18_cls4.txt](from-NCSC/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                         | 5              |
| [from-NCSC/pwlist_cc_len19_cls1.txt](from-NCSC/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                         | 226            |
| [from-NCSC/pwlist_cc_len19_cls2.txt](from-NCSC/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                         | 90             |
| [from-NCSC/pwlist_cc_len19_cls3.txt](from-NCSC/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                         | 41             |
| [from-NCSC/pwlist_cc_len19_cls4.txt](from-NCSC/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                         | 5              |
| [from-NCSC/pwlist_cc_len20_cls1.txt](from-NCSC/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                         | 204            |
| [from-NCSC/pwlist_cc_len20_cls2.txt](from-NCSC/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                         | 73             |
| [from-NCSC/pwlist_cc_len20_cls3.txt](from-NCSC/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                         | 32             |
| [from-NCSC/pwlist_cc_len20_cls4.txt](from-NCSC/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                         | 5              |

