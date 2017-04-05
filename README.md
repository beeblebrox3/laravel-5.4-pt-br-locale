# Arquivos de linguagem do Laravel 5.4 - Português do Brasil

## Instalação

1. Clonar este projeto para uma pasta dentro de `resources/lang/`
  ```
  $ cd resources/lang/
  $ git clone https://github.com/EscolaMavins/laravel-5.4-pt-br-localization.git ./pt-br
  ```
  
Você pode remover o `README.md` e o diretório oculto `.git` para poder incluir
e versionar os arquivos deste projeto no seu repositório.

  ```
  $ rm -rf pt-br/.git/ pt-br/README.md
  ```
  
2. Configurar o Laravel para utilizar o português por padrão:

  ```
  // Linha 68 do arquivo config/app.php
  'locale' => 'pt-br',
  ```

**Nota:** adaptado de
[felipeporto](https://github.com/felipeporto/laravel-5.2-pt-br-localization)
para o Laravel 5.4.
