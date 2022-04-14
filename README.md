
# Arquivos de configurações básicas

- Os arquivos encontrados neste repositório são de configurações de projetos em 'java'. Estes arquivos se repetem  em muitos projetos.

- Para fazcilitar a criação de um projeto novo, esse repositório guarda esses asquivos de configurações básicas.

## Arquivos disponíveis

> `1) POM.XML`

- Este arquivo encontra-se na raíz de projetos maven. O mavem fica resposável por gerenciar as dependêcias informadas pelo usuário.
- O arquivo presente neste repositório está pronto com dependêncais do __Spring Framework__.

Dependêncais inseridas: (apenas para exemplo)
- [x] Spring Web
- [x] Thymeleaf
- [x] Spring Data JPA
- [x] MySQL Driver
- [x] Spring Boot DevTools

> `2) PERSISTENSE.XML`

Usado pelo __Java Persistense API - JPA__, o arquivo guarda informações de acesso a base de dados. No arquivo disponível neste repositório está configurado para acessar base de dados __MySQL__.

> `3) APPLICATION.PROPERTIES`

Serve para armazenar propriedades de escopo de aplicativo. O arquivo presente neste repositório já vem com propriedades de acesso a base de dados __MySQL__.
