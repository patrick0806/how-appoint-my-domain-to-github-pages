# How to point my domain to github pages

In the Domain provider, go to DNS settings and add four type A records with the following information:

| Name | record type | value |
| --- | --- | --- |
| --- | A | 185.199.108.153 |
| --- | A | 185.199.109.153 |
| --- | A | 185.199.110.153 |
| --- | A | 185.199.111.153 |

**Note: The name value is clean but depending on the platform it is hosted on, domino will be asked to put the @ in the name's place**

After entering this information, let's create a new record of type CNAME

| Name | record type | value |
| --- | --- | --- |
| www | CNAME | ytechsolucoes.com |
