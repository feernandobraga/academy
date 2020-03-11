CIDR calculator: https://cidr.xyz/


| IP address | IP in binary | subnet in binary |  subnet in decimals | private/public | hosts available in AWS |
--- | ---| --- | --- | --- | --- |
| 10.0.0.1/24 |  `11000000.10101000.00000000.00000001` | `11111111.11111111.11111111.00000000` | `255.255.255.0` | `private` | `251`|
| 192.168.0.1/16 |  `11000000.10101000.00000000.00000001` | `11111111.11111111.00000000.00000000` | `255.255.0.0` | `private` | `65531`|
| 249.165.166.135/30 |  `11111001.10100101.10100110.10000111` | `11111111.11111111.11111111.11111100` | `255.255.255.252` | `public` | `4 hosts. Too small for AWS, minimum is /28 with 16 addresses` |
| 236.68.223.18/32 |  `11101100.01000100.11011111.00010010` | `11111111.11111111.11111111.11111111` | `255.255.255.255` | `public` | `1 host, Too small for AWS, minimum is /28 with 16 addresses`|
| 172.31.0.0/16 |  `10101100.00011111.00000000.00000000` | `11111111.11111111.00000000.00000000` | `255.255.0.0` | `private` | `65531` |