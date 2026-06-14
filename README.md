# Bíblias Papiros

Bem-vindo ao repositório de traduções e manuscritos bíblicos do projeto **Papiros da Verdade**. 
Aqui você encontrará diversas versões da Bíblia estruturadas em arquivos JSON (com `book`, `chapter`, `verse` e `text_content`) prontas para uso em sua própria API, banco de dados ou aplicação mobile.

## 📚 Fontes, Referências e Créditos

Este repositório não seria possível sem a contribuição inestimável da comunidade Open-Source, que trabalhou por anos catalogando, normalizando e digitando estas traduções sagradas para domínio público ou uso acadêmico. 

Listamos abaixo os repositórios vitais que forneceram a essência e o texto bruto que unificamos em nossa base:

1. **[biblias-main](https://github.com/thiagobodruk/biblias)**: Repositório essencial que compilou de forma excepcional os textos das principais traduções em português (ACF, ARA, ARC, NVI, NAA, NTLH, etc) com rigor métrico. Nossa imensa gratidão!
2. **[bible-data-main (Alamo Polyglot)](https://github.com/Alamo-Bible/AlamoPolyglot)**: Extraímos e normalizamos textos clássicos internacionais, manuscritos hebraicos (WLC) e gregos clássicos (ALEX), além das clássicas em inglês (KJV, WEB).
3. Bases do **`interactive-bible-timeline`**, **`KJV-bible-database-with-metadata-MetaV`** e bibliotecas `berean-study-bible`.

Sinta-se encorajado a visitar, apoiar e referenciar os repositórios originais!

## ⚠️ Nota Importante sobre Variações

Os textos aqui disponibilizados foram consolidados em um banco de dados PostgreSQL relacional único e exportados para o formato JSON final. 
Apesar de um grande esforço de limpeza de caracteres especiais e *encoding*, alguns versículos em traduções muito antigas ou apócrifas podem conter variações de diagramação ou pontuação que refletem os manuscritos digitais de origem. 
Se você é desenvolvedor e encontrar qualquer anomalia textual (*typos* ou erros de formatação JSON), encorajamos que abra um **Pull Request**.

## 🚀 Como Utilizar

Cada arquivo no diretório raiz representa uma tradução completa da Bíblia.
Por exemplo, o arquivo `ACF.json` traz o texto da Almeida Corrigida Fiel. 
Os atributos JSON são muito limpos e simples de popular em um banco NoSQL (MongoDB/Firebase) ou de dar um *Seed* num banco relacional (MySQL/Postgres).
