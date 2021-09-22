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

| Filename           | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [pwlist_an_len10.txt](from-top-1M/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                        | 68717          |
| [pwlist_an_len11.txt](from-top-1M/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                        | 40370          |
| [pwlist_an_len12.txt](from-top-1M/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                        | 27387          |
| [pwlist_an_len13.txt](from-top-1M/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                        | 17796          |
| [pwlist_an_len14.txt](from-top-1M/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                        | 9548           |
| [pwlist_an_len15.txt](from-top-1M/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                        | 5800           |
| [pwlist_an_len16.txt](from-top-1M/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                        | 3385           |
| [pwlist_an_len17.txt](from-top-1M/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                        | 1699           |
| [pwlist_an_len18.txt](from-top-1M/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                        | 1179           |
| [pwlist_an_len19.txt](from-top-1M/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                        | 801            |
| [pwlist_an_len20.txt](from-top-1M/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                        | 552            |
| [pwlist_anm_len10.txt](from-top-1M/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                        | 16884          |
| [pwlist_anm_len11.txt](from-top-1M/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                        | 11029          |
| [pwlist_anm_len12.txt](from-top-1M/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                        | 9200           |
| [pwlist_anm_len13.txt](from-top-1M/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                        | 6898           |
| [pwlist_anm_len14.txt](from-top-1M/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                        | 1789           |
| [pwlist_anm_len15.txt](from-top-1M/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                        | 1003           |
| [pwlist_anm_len16.txt](from-top-1M/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                        | 675            |
| [pwlist_anm_len17.txt](from-top-1M/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                        | 285            |
| [pwlist_anm_len18.txt](from-top-1M/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                        | 222            |
| [pwlist_anm_len19.txt](from-top-1M/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                        | 170            |
| [pwlist_anm_len20.txt](from-top-1M/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                        | 127            |
| [pwlist_ns_len10.txt](from-top-1M/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                        | 108155         |
| [pwlist_ns_len11.txt](from-top-1M/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                        | 62302          |
| [pwlist_ns_len12.txt](from-top-1M/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                        | 40507          |
| [pwlist_ns_len13.txt](from-top-1M/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                        | 25231          |
| [pwlist_ns_len14.txt](from-top-1M/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                        | 13387          |
| [pwlist_ns_len15.txt](from-top-1M/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                        | 8217           |
| [pwlist_ns_len16.txt](from-top-1M/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                        | 4762           |
| [pwlist_ns_len17.txt](from-top-1M/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                        | 2459           |
| [pwlist_ns_len18.txt](from-top-1M/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                        | 1682           |
| [pwlist_ns_len19.txt](from-top-1M/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                        | 1089           |
| [pwlist_ns_len20.txt](from-top-1M/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                        | 735            |
| [pwlist_cc_len10_cls1.txt](from-top-1M/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                        | 113360         |
| [pwlist_cc_len10_cls2.txt](from-top-1M/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                        | 77410          |
| [pwlist_cc_len10_cls3.txt](from-top-1M/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                        | 18989          |
| [pwlist_cc_len10_cls4.txt](from-top-1M/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                        | 959            |
| [pwlist_cc_len11_cls1.txt](from-top-1M/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                        | 66644          |
| [pwlist_cc_len11_cls2.txt](from-top-1M/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                        | 46916          |
| [pwlist_cc_len11_cls3.txt](from-top-1M/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                        | 12775          |
| [pwlist_cc_len11_cls4.txt](from-top-1M/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                        | 872            |
| [pwlist_cc_len12_cls1.txt](from-top-1M/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                        | 44149          |
| [pwlist_cc_len12_cls2.txt](from-top-1M/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                        | 32729          |
| [pwlist_cc_len12_cls3.txt](from-top-1M/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                        | 10674          |
| [pwlist_cc_len12_cls4.txt](from-top-1M/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                        | 702            |
| [pwlist_cc_len13_cls1.txt](from-top-1M/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                        | 28257          |
| [pwlist_cc_len13_cls2.txt](from-top-1M/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                        | 21861          |
| [pwlist_cc_len13_cls3.txt](from-top-1M/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                        | 8142           |
| [pwlist_cc_len13_cls4.txt](from-top-1M/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                        | 542            |
| [pwlist_cc_len14_cls1.txt](from-top-1M/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                        | 15533          |
| [pwlist_cc_len14_cls2.txt](from-top-1M/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                        | 11224          |
| [pwlist_cc_len14_cls3.txt](from-top-1M/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                        | 2575           |
| [pwlist_cc_len14_cls4.txt](from-top-1M/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                        | 352            |
| [pwlist_cc_len15_cls1.txt](from-top-1M/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                        | 9747           |
| [pwlist_cc_len15_cls2.txt](from-top-1M/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                        | 6979           |
| [pwlist_cc_len15_cls3.txt](from-top-1M/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                        | 1569           |
| [pwlist_cc_len15_cls4.txt](from-top-1M/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                        | 186            |
| [pwlist_cc_len16_cls1.txt](from-top-1M/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                        | 5936           |
| [pwlist_cc_len16_cls2.txt](from-top-1M/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                        | 4225           |
| [pwlist_cc_len16_cls3.txt](from-top-1M/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                        | 1108           |
| [pwlist_cc_len16_cls4.txt](from-top-1M/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                        | 157            |
| [pwlist_cc_len17_cls1.txt](from-top-1M/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                        | 3171           |
| [pwlist_cc_len17_cls2.txt](from-top-1M/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                        | 2207           |
| [pwlist_cc_len17_cls3.txt](from-top-1M/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                        | 590            |
| [pwlist_cc_len17_cls4.txt](from-top-1M/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                        | 57             |
| [pwlist_cc_len18_cls1.txt](from-top-1M/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                        | 2202           |
| [pwlist_cc_len18_cls2.txt](from-top-1M/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                        | 1527           |
| [pwlist_cc_len18_cls3.txt](from-top-1M/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                        | 444            |
| [pwlist_cc_len18_cls4.txt](from-top-1M/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                        | 45             |
| [pwlist_cc_len19_cls1.txt](from-top-1M/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                        | 1495           |
| [pwlist_cc_len19_cls2.txt](from-top-1M/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                        | 1060           |
| [pwlist_cc_len19_cls3.txt](from-top-1M/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                        | 346            |
| [pwlist_cc_len19_cls4.txt](from-top-1M/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                        | 34             |
| [pwlist_cc_len20_cls1.txt](from-top-1M/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                        | 1020           |
| [pwlist_cc_len20_cls2.txt](from-top-1M/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                        | 720            |
| [pwlist_cc_len20_cls3.txt](from-top-1M/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                        | 252            |
| [pwlist_cc_len20_cls4.txt](from-top-1M/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                        | 23             |


## From the Rockyou list

These were extracted from the well-known "rockyou.txt" password list.

Some preprocessing was performed to remove passwords that are unlikely to be re-used elsewhere, e.g. passwords that were just rockyou URLs.

| Filename           | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [pwlist_an_len10.txt](from-rockyou/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                        | 2236661        |
| [pwlist_an_len11.txt](from-rockyou/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                        | 1226645        |
| [pwlist_an_len12.txt](from-rockyou/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                        | 798023         |
| [pwlist_an_len13.txt](from-rockyou/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                        | 514488         |
| [pwlist_an_len14.txt](from-rockyou/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                        | 329007         |
| [pwlist_an_len15.txt](from-rockyou/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                        | 194196         |
| [pwlist_an_len16.txt](from-rockyou/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                        | 109456         |
| [pwlist_an_len17.txt](from-rockyou/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                        | 43226          |
| [pwlist_an_len18.txt](from-rockyou/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                        | 26049          |
| [pwlist_an_len19.txt](from-rockyou/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                        | 16604          |
| [pwlist_an_len20.txt](from-rockyou/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                        | 10980          |
| [pwlist_anm_len10.txt](from-rockyou/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                        | 150544         |
| [pwlist_anm_len11.txt](from-rockyou/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                        | 87375          |
| [pwlist_anm_len12.txt](from-rockyou/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                        | 57935          |
| [pwlist_anm_len13.txt](from-rockyou/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                        | 37499          |
| [pwlist_anm_len14.txt](from-rockyou/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                        | 24770          |
| [pwlist_anm_len15.txt](from-rockyou/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                        | 15714          |
| [pwlist_anm_len16.txt](from-rockyou/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                        | 9073           |
| [pwlist_anm_len17.txt](from-rockyou/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                        | 3378           |
| [pwlist_anm_len18.txt](from-rockyou/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                        | 2016           |
| [pwlist_anm_len19.txt](from-rockyou/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                        | 1294           |
| [pwlist_anm_len20.txt](from-rockyou/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                        | 861            |
| [pwlist_ns_len10.txt](from-rockyou/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                        | 3964740        |
| [pwlist_ns_len11.txt](from-rockyou/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                        | 2097309        |
| [pwlist_ns_len12.txt](from-rockyou/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                        | 1318487        |
| [pwlist_ns_len13.txt](from-rockyou/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                        | 829026         |
| [pwlist_ns_len14.txt](from-rockyou/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                        | 513682         |
| [pwlist_ns_len15.txt](from-rockyou/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                        | 302339         |
| [pwlist_ns_len16.txt](from-rockyou/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                        | 169380         |
| [pwlist_ns_len17.txt](from-rockyou/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                        | 76835          |
| [pwlist_ns_len18.txt](from-rockyou/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                        | 48091          |
| [pwlist_ns_len19.txt](from-rockyou/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                        | 30489          |
| [pwlist_ns_len20.txt](from-rockyou/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                        | 20109          |
| [pwlist_cc_len10_cls1.txt](from-rockyou/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                        | 4418859        |
| [pwlist_cc_len10_cls2.txt](from-rockyou/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                        | 2484937        |
| [pwlist_cc_len10_cls3.txt](from-rockyou/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                        | 396005         |
| [pwlist_cc_len10_cls4.txt](from-rockyou/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                        | 24400          |
| [pwlist_cc_len11_cls1.txt](from-rockyou/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                        | 2405509        |
| [pwlist_cc_len11_cls2.txt](from-rockyou/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                        | 1386831        |
| [pwlist_cc_len11_cls3.txt](from-rockyou/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                        | 262435         |
| [pwlist_cc_len11_cls4.txt](from-rockyou/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                        | 15396          |
| [pwlist_cc_len12_cls1.txt](from-rockyou/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                        | 1540650        |
| [pwlist_cc_len12_cls2.txt](from-rockyou/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                        | 909214         |
| [pwlist_cc_len12_cls3.txt](from-rockyou/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                        | 186551         |
| [pwlist_cc_len12_cls4.txt](from-rockyou/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                        | 10923          |
| [pwlist_cc_len13_cls1.txt](from-rockyou/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                        | 986182         |
| [pwlist_cc_len13_cls2.txt](from-rockyou/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                        | 590492         |
| [pwlist_cc_len13_cls3.txt](from-rockyou/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                        | 130013         |
| [pwlist_cc_len13_cls4.txt](from-rockyou/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                        | 7517           |
| [pwlist_cc_len14_cls1.txt](from-rockyou/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                        | 622688         |
| [pwlist_cc_len14_cls2.txt](from-rockyou/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                        | 380268         |
| [pwlist_cc_len14_cls3.txt](from-rockyou/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                        | 89760          |
| [pwlist_cc_len14_cls4.txt](from-rockyou/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                        | 5242           |
| [pwlist_cc_len15_cls1.txt](from-rockyou/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                        | 374999         |
| [pwlist_cc_len15_cls2.txt](from-rockyou/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                        | 227923         |
| [pwlist_cc_len15_cls3.txt](from-rockyou/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                        | 59042          |
| [pwlist_cc_len15_cls4.txt](from-rockyou/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                        | 3513           |
| [pwlist_cc_len16_cls1.txt](from-rockyou/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                        | 214679         |
| [pwlist_cc_len16_cls2.txt](from-rockyou/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                        | 130732         |
| [pwlist_cc_len16_cls3.txt](from-rockyou/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                        | 35545          |
| [pwlist_cc_len16_cls4.txt](from-rockyou/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                        | 2247           |
| [pwlist_cc_len17_cls1.txt](from-rockyou/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                        | 97521          |
| [pwlist_cc_len17_cls2.txt](from-rockyou/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                        | 54614          |
| [pwlist_cc_len17_cls3.txt](from-rockyou/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                        | 13608          |
| [pwlist_cc_len17_cls4.txt](from-rockyou/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                        | 1089           |
| [pwlist_cc_len18_cls1.txt](from-rockyou/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                        | 62048          |
| [pwlist_cc_len18_cls2.txt](from-rockyou/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                        | 33953          |
| [pwlist_cc_len18_cls3.txt](from-rockyou/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                        | 8647           |
| [pwlist_cc_len18_cls4.txt](from-rockyou/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                        | 731            |
| [pwlist_cc_len19_cls1.txt](from-rockyou/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                        | 40592          |
| [pwlist_cc_len19_cls2.txt](from-rockyou/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                        | 22323          |
| [pwlist_cc_len19_cls3.txt](from-rockyou/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                        | 6020           |
| [pwlist_cc_len19_cls4.txt](from-rockyou/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                        | 510            |
| [pwlist_cc_len20_cls1.txt](from-rockyou/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                        | 27582          |
| [pwlist_cc_len20_cls2.txt](from-rockyou/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                        | 15222          |
| [pwlist_cc_len20_cls3.txt](from-rockyou/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                        | 4315           |
| [pwlist_cc_len20_cls4.txt](from-rockyou/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                        | 370            |

## From the NCSC top 100k

These were extracted from the [NCSC top 100k password list](https://www.ncsc.gov.uk/news/most-hacked-passwords-revealed-as-uk-cyber-survey-exposes-gaps-in-online-security), published in 2019.

| Filename           | Policy Type        | Minimum Characters | Minimum Character Classes | Password Count |
| ------------------ | ------------------ | ------------------ | ------------------------- | -------------- |
| [pwlist_an_len10.txt](from-NCSC/pwlist_an_len10.txt) | Alphanumeric       | 10                 | -                        | 5881           |
| [pwlist_an_len11.txt](from-NCSC/pwlist_an_len11.txt) | Alphanumeric       | 11                 | -                        | 1002           |
| [pwlist_an_len12.txt](from-NCSC/pwlist_an_len12.txt) | Alphanumeric       | 12                 | -                        | 583            |
| [pwlist_an_len13.txt](from-NCSC/pwlist_an_len13.txt) | Alphanumeric       | 13                 | -                        | 328            |
| [pwlist_an_len14.txt](from-NCSC/pwlist_an_len14.txt) | Alphanumeric       | 14                 | -                        | 240            |
| [pwlist_an_len15.txt](from-NCSC/pwlist_an_len15.txt) | Alphanumeric       | 15                 | -                        | 179            |
| [pwlist_an_len16.txt](from-NCSC/pwlist_an_len16.txt) | Alphanumeric       | 16                 | -                        | 134            |
| [pwlist_an_len17.txt](from-NCSC/pwlist_an_len17.txt) | Alphanumeric       | 17                 | -                        | 101            |
| [pwlist_an_len18.txt](from-NCSC/pwlist_an_len18.txt) | Alphanumeric       | 18                 | -                        | 87             |
| [pwlist_an_len19.txt](from-NCSC/pwlist_an_len19.txt) | Alphanumeric       | 19                 | -                        | 70             |
| [pwlist_an_len20.txt](from-NCSC/pwlist_an_len20.txt) | Alphanumeric       | 20                 | -                        | 55             |
| [pwlist_anm_len10.txt](from-NCSC/pwlist_anm_len10.txt) | Mixed Alphanumeric | 10                 | -                        | 564            |
| [pwlist_anm_len11.txt](from-NCSC/pwlist_anm_len11.txt) | Mixed Alphanumeric | 11                 | -                        | 88             |
| [pwlist_anm_len12.txt](from-NCSC/pwlist_anm_len12.txt) | Mixed Alphanumeric | 12                 | -                        | 54             |
| [pwlist_anm_len13.txt](from-NCSC/pwlist_anm_len13.txt) | Mixed Alphanumeric | 13                 | -                        | 31             |
| [pwlist_anm_len14.txt](from-NCSC/pwlist_anm_len14.txt) | Mixed Alphanumeric | 14                 | -                        | 22             |
| [pwlist_anm_len15.txt](from-NCSC/pwlist_anm_len15.txt) | Mixed Alphanumeric | 15                 | -                        | 19             |
| [pwlist_anm_len16.txt](from-NCSC/pwlist_anm_len16.txt) | Mixed Alphanumeric | 16                 | -                        | 12             |
| [pwlist_anm_len17.txt](from-NCSC/pwlist_anm_len17.txt) | Mixed Alphanumeric | 17                 | -                        | 9              |
| [pwlist_anm_len18.txt](from-NCSC/pwlist_anm_len18.txt) | Mixed Alphanumeric | 18                 | -                        | 7              |
| [pwlist_anm_len19.txt](from-NCSC/pwlist_anm_len19.txt) | Mixed Alphanumeric | 19                 | -                        | 6              |
| [pwlist_anm_len20.txt](from-NCSC/pwlist_anm_len20.txt) | Mixed Alphanumeric | 20                 | -                        | 6              |
| [pwlist_ns_len10.txt](from-NCSC/pwlist_ns_len10.txt) | No Symbols         | 10                 | -                        | 8720           |
| [pwlist_ns_len11.txt](from-NCSC/pwlist_ns_len11.txt) | No Symbols         | 11                 | -                        | 1811           |
| [pwlist_ns_len12.txt](from-NCSC/pwlist_ns_len12.txt) | No Symbols         | 12                 | -                        | 933            |
| [pwlist_ns_len13.txt](from-NCSC/pwlist_ns_len13.txt) | No Symbols         | 13                 | -                        | 436            |
| [pwlist_ns_len14.txt](from-NCSC/pwlist_ns_len14.txt) | No Symbols         | 14                 | -                        | 271            |
| [pwlist_ns_len15.txt](from-NCSC/pwlist_ns_len15.txt) | No Symbols         | 15                 | -                        | 186            |
| [pwlist_ns_len16.txt](from-NCSC/pwlist_ns_len16.txt) | No Symbols         | 16                 | -                        | 119            |
| [pwlist_ns_len17.txt](from-NCSC/pwlist_ns_len17.txt) | No Symbols         | 17                 | -                        | 66             |
| [pwlist_ns_len18.txt](from-NCSC/pwlist_ns_len18.txt) | No Symbols         | 18                 | -                        | 55             |
| [pwlist_ns_len19.txt](from-NCSC/pwlist_ns_len19.txt) | No Symbols         | 19                 | -                        | 41             |
| [pwlist_ns_len20.txt](from-NCSC/pwlist_ns_len20.txt) | No Symbols         | 20                 | -                        | 32             |
| [pwlist_cc_len10_cls1.txt](from-NCSC/pwlist_cc_len10_cls1.txt) | Class Count        | 10                 | 1                        | 9434           |
| [pwlist_cc_len10_cls2.txt](from-NCSC/pwlist_cc_len10_cls2.txt) | Class Count        | 10                 | 2                        | 6234           |
| [pwlist_cc_len10_cls3.txt](from-NCSC/pwlist_cc_len10_cls3.txt) | Class Count        | 10                 | 3                        | 755            |
| [pwlist_cc_len10_cls4.txt](from-NCSC/pwlist_cc_len10_cls4.txt) | Class Count        | 10                 | 4                        | 18             |
| [pwlist_cc_len11_cls1.txt](from-NCSC/pwlist_cc_len11_cls1.txt) | Class Count        | 11                 | 1                        | 2344           |
| [pwlist_cc_len11_cls2.txt](from-NCSC/pwlist_cc_len11_cls2.txt) | Class Count        | 11                 | 2                        | 1212           |
| [pwlist_cc_len11_cls3.txt](from-NCSC/pwlist_cc_len11_cls3.txt) | Class Count        | 11                 | 3                        | 230            |
| [pwlist_cc_len11_cls4.txt](from-NCSC/pwlist_cc_len11_cls4.txt) | Class Count        | 11                 | 4                        | 12             |
| [pwlist_cc_len12_cls1.txt](from-NCSC/pwlist_cc_len12_cls1.txt) | Class Count        | 12                 | 1                        | 1404           |
| [pwlist_cc_len12_cls2.txt](from-NCSC/pwlist_cc_len12_cls2.txt) | Class Count        | 12                 | 2                        | 758            |
| [pwlist_cc_len12_cls3.txt](from-NCSC/pwlist_cc_len12_cls3.txt) | Class Count        | 12                 | 3                        | 164            |
| [pwlist_cc_len12_cls4.txt](from-NCSC/pwlist_cc_len12_cls4.txt) | Class Count        | 12                 | 4                        | 10             |
| [pwlist_cc_len13_cls1.txt](from-NCSC/pwlist_cc_len13_cls1.txt) | Class Count        | 13                 | 1                        | 829            |
| [pwlist_cc_len13_cls2.txt](from-NCSC/pwlist_cc_len13_cls2.txt) | Class Count        | 13                 | 2                        | 461            |
| [pwlist_cc_len13_cls3.txt](from-NCSC/pwlist_cc_len13_cls3.txt) | Class Count        | 13                 | 3                        | 131            |
| [pwlist_cc_len13_cls4.txt](from-NCSC/pwlist_cc_len13_cls4.txt) | Class Count        | 13                 | 4                        | 6              |
| [pwlist_cc_len14_cls1.txt](from-NCSC/pwlist_cc_len14_cls1.txt) | Class Count        | 14                 | 1                        | 623            |
| [pwlist_cc_len14_cls2.txt](from-NCSC/pwlist_cc_len14_cls2.txt) | Class Count        | 14                 | 2                        | 343            |
| [pwlist_cc_len14_cls3.txt](from-NCSC/pwlist_cc_len14_cls3.txt) | Class Count        | 14                 | 3                        | 106            |
| [pwlist_cc_len14_cls4.txt](from-NCSC/pwlist_cc_len14_cls4.txt) | Class Count        | 14                 | 4                        | 6              |
| [pwlist_cc_len15_cls1.txt](from-NCSC/pwlist_cc_len15_cls1.txt) | Class Count        | 15                 | 1                        | 486            |
| [pwlist_cc_len15_cls2.txt](from-NCSC/pwlist_cc_len15_cls2.txt) | Class Count        | 15                 | 2                        | 261            |
| [pwlist_cc_len15_cls3.txt](from-NCSC/pwlist_cc_len15_cls3.txt) | Class Count        | 15                 | 3                        | 89             |
| [pwlist_cc_len15_cls4.txt](from-NCSC/pwlist_cc_len15_cls4.txt) | Class Count        | 15                 | 4                        | 6              |
| [pwlist_cc_len16_cls1.txt](from-NCSC/pwlist_cc_len16_cls1.txt) | Class Count        | 16                 | 1                        | 386            |
| [pwlist_cc_len16_cls2.txt](from-NCSC/pwlist_cc_len16_cls2.txt) | Class Count        | 16                 | 2                        | 192            |
| [pwlist_cc_len16_cls3.txt](from-NCSC/pwlist_cc_len16_cls3.txt) | Class Count        | 16                 | 3                        | 73             |
| [pwlist_cc_len16_cls4.txt](from-NCSC/pwlist_cc_len16_cls4.txt) | Class Count        | 16                 | 4                        | 6              |
| [pwlist_cc_len17_cls1.txt](from-NCSC/pwlist_cc_len17_cls1.txt) | Class Count        | 17                 | 1                        | 297            |
| [pwlist_cc_len17_cls2.txt](from-NCSC/pwlist_cc_len17_cls2.txt) | Class Count        | 17                 | 2                        | 140            |
| [pwlist_cc_len17_cls3.txt](from-NCSC/pwlist_cc_len17_cls3.txt) | Class Count        | 17                 | 3                        | 62             |
| [pwlist_cc_len17_cls4.txt](from-NCSC/pwlist_cc_len17_cls4.txt) | Class Count        | 17                 | 4                        | 6              |
| [pwlist_cc_len18_cls1.txt](from-NCSC/pwlist_cc_len18_cls1.txt) | Class Count        | 18                 | 1                        | 269            |
| [pwlist_cc_len18_cls2.txt](from-NCSC/pwlist_cc_len18_cls2.txt) | Class Count        | 18                 | 2                        | 118            |
| [pwlist_cc_len18_cls3.txt](from-NCSC/pwlist_cc_len18_cls3.txt) | Class Count        | 18                 | 3                        | 52             |
| [pwlist_cc_len18_cls4.txt](from-NCSC/pwlist_cc_len18_cls4.txt) | Class Count        | 18                 | 4                        | 5              |
| [pwlist_cc_len19_cls1.txt](from-NCSC/pwlist_cc_len19_cls1.txt) | Class Count        | 19                 | 1                        | 226            |
| [pwlist_cc_len19_cls2.txt](from-NCSC/pwlist_cc_len19_cls2.txt) | Class Count        | 19                 | 2                        | 90             |
| [pwlist_cc_len19_cls3.txt](from-NCSC/pwlist_cc_len19_cls3.txt) | Class Count        | 19                 | 3                        | 41             |
| [pwlist_cc_len19_cls4.txt](from-NCSC/pwlist_cc_len19_cls4.txt) | Class Count        | 19                 | 4                        | 5              |
| [pwlist_cc_len20_cls1.txt](from-NCSC/pwlist_cc_len20_cls1.txt) | Class Count        | 20                 | 1                        | 204            |
| [pwlist_cc_len20_cls2.txt](from-NCSC/pwlist_cc_len20_cls2.txt) | Class Count        | 20                 | 2                        | 73             |
| [pwlist_cc_len20_cls3.txt](from-NCSC/pwlist_cc_len20_cls3.txt) | Class Count        | 20                 | 3                        | 32             |
| [pwlist_cc_len20_cls4.txt](from-NCSC/pwlist_cc_len20_cls4.txt) | Class Count        | 20                 | 4                        | 5              |

