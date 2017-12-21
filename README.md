#  Linguagem do Laravel 5.5 - Português de Portugal

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/ ./pt-PT
  ```
  
  Pode remover a pasta .git.

  ```
  $ rm -r pt-PT/.git/
  ```
  
2. Configurar o Framework para utilizar a linguagem PT por omissão
  ```
  // Linha 81 do ficheiro config/app.php
  'locale' => 'pt-PT',
  ```
