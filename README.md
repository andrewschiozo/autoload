# Autoload
Autoload com namespaces (PSR-4)

### Motivação
Cansei de criar esse arquvio em todos os projetos relâmpagos

### Começando
src/MinhaClasse.php
```
<?php

namespace src;

class MinhaClasse{
  //public function __consctruct(){}
}
```

index.php
```
<?php
  require_once 'Autoload.php';
  new Autoload();
  
  $mc = new MinhaClasse();
```
### Pré requisitos
PHP ^5.6

### Instalação
Basta copiar o arquivo Autoload.php e colar na raíz do seu projeto.
```
/meuprojeto/
  src/
    MinhaClasse.php
  views/
    ...
  Autoload.php
  index.php/
```
### Agradecimentos
Obrigado =)
