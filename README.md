# Como apontar meu dominio para o github pages

No provedor do Domínio vá nas configurações DNS e adicione quatro registros do tipo A com a seguintes informações:

| Nome | tipo de registro | valor |
| --- | --- | --- |
| --- | A | 185.199.108.153 |
| --- | A | 185.199.109.153 |
| --- | A | 185.199.110.153 |
| --- | A | 185.199.111.153 |

**Obs: O valor nome está limpo mas dependendo da plataforma em que estiver hospedado o domino vai ser pedido para colocar o @ no local do nome**

Após inserido essas informações, vamos criar um novo registro do tipo CNAME

| Nome | tipo de registro | valor |
| --- | --- | --- |
| www | CNAME | ytechsolucoes.com |
