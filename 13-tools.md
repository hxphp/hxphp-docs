----
## *Tools* {#tools}

Nesta seção você irá conhecer o objeto auxiliar *Tools*.
----
### Métodos auxiliares {#metodos-auxiliares}

O objeto *Tools* é uma ferramenta de apoio geral, ou seja, trata-se de um objeto que contém métodos comuns com funções de filtro, tratamento, criptografia e afins.

Por padrão, este objeto contém os seguintes métodos **estáticos**:

+ `dd($data, $dump = false)` - Exibe os dados;
+ `hashHX($password, $salt = null)` - Criptografa a senha do usuário no padrão HXPHP;
+ `filteredName($input)` - Processo de tratamento para o mecanismo MVC;
+ `filteredFileName($input)`, e;
+ `decamelize($cameled, [$sep])`;


Tools na prática:
```php
	\HXPHP\System\Tools::hashHX($post['password']);
```