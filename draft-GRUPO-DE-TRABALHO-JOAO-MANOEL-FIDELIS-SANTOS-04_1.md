**Working Group Name**  **J. Fidelis**
  
Internet Draft         DComp/UFS

Intended status: EXPERIMENTAL         XXX 0, 0000

Expires: Fail 0000


# Title draft-GRUPO-DE-TRABALHO-JOAO-MANOEL-FIDELIS-SANTOS-04.txt


## Status deste memorando

Este rascunho da Internet é submetido em total conformidade com as disposições do BCP 78 e BCP 79.
Este documento não pode ser modificado e seus trabalhos derivados não podem ser criados, exceto para publicação
como um RFC e traduzi-lo para outros idiomas que não o inglês.

Este documento pode conter material de documentos da IETF ou de contribuições da IETF publicadas ou feitas publicamente
disponível antes de 10 de novembro de 2008. As pessoas que controlam os direitos autorais de alguns desses materiais podem
não concedeu à IETF Trust o direito de permitir modificações desse material fora do processo de normas da IETF.
Sem obter uma licença adequada das pessoas que controlam os direitos autorais de tais materiais, este documento pode
não pode ser modificado fora do Processo de Normas da IETF, e seus trabalhos derivados não podem ser criados fora da IETF
Processo de Normas, exceto para formatá-lo para publicação em RFC ou traduzi-lo para outros idiomas que não o inglês.

Rascunhos da Internet são documentos de trabalho da Internet Engineering Task Force (IETF), de suas áreas e de seus grupos de trabalho.
Observe que outros grupos também podem distribuir documentos de trabalho como rascunhos na Internet.
Rascunhos na Internet são rascunhos de documentos válidos por um período máximo de seis meses e podem ser atualizados, substituídos,
ou obsoleto por outros documentos a qualquer momento. É inapropriado usar Rascunhos da Internet como material de referência ou citar
eles que não sejam "trabalhos em andamento".
A lista dos rascunhos atuais da Internet pode ser acessada em http://www.ietf.org/ietf/1id-abstracts.txt
A lista de diretórios-sombra da Internet pode ser acessada em http://www.ietf.org/shadow.html
Este rascunho da Internet expirará na falha 19, 0000.
## Aviso de direitos autorais
Copyright (c) 0000 IETF Trust e as pessoas identificadas como autores do documento. Todos os direitos reservados.

Este documento está sujeito ao BCP 78 e às disposições legais da IETF Trust relacionadas aos documentos da IETF
(http://trustee.ietf.org/license-info) em vigor na data de publicação deste documento. Por favor
revise esses documentos cuidadosamente, pois eles descrevem seus direitos e restrições em relação a este documento.

## Abstract
> Digite seu resumo aqui. Normalmente, de 5 a 10 linhas, nunca menos que 3 e nem mais que 20 linhas

## 1. Introdução
Esta seção geralmente é intitulada “Introdução ao protocolo HTTP que usa o serviço de servidor-cliente, foi considerado uma extensão do protocolo HTTP para a consumação de uma localização geográfica de um site.

Tem sido um problema antigo relacionar números de IP a localizações geográficas. A disponibilidade da localização geográfica. As informações têm aplicações imediatas no gerenciamento de rede. A utilidade e funcionalidade destes já amplamente ferramentas usadas seriam bastante aprimoradas com o fornecimento de informações de localização geográfica.

A maneira ideal de gerenciar e manter um banco de dados de informações, como como localização geográfica dos hosts da Internet, é delegar responsabilidade aos administradores de domínio local. Uma grande distribuição banco de dados pode ser implementado com um mecanismo simples de atualização a informação local. Um mecanismo de consulta também deve estar disponível para verificar entradas locais, bem como perguntar sobre dados de domínios não locais.

## 2. Convenções usadas neste documento

Nos exemplos, "C:" e "S:" indicam linhas enviadas pelo cliente e pelo servidor, respectivamente. As palavras-chave "DEVEM", "NÃO DEVEM", "NECESSÁRIO", "DEVEM", "NÃO DEVEM", "DEVEM", "NÃO DEVEM", "RECOMENDADO", "PODE" e "OPCIONAL" neste documento são para ser interpretado como descrito na RFC 2119 [RFC2119].

Neste documento, essas palavras aparecerão com essa interpretação somente quando estiver em TODOS OS CAPS. As letras minúsculas dessas palavras não devem ser interpretadas como tendo significado descrito na RFC 2119.

Neste documento, os caracteres ">>" que precedem as linhas recuadas indicam uma declaração usando as palavras-chave listadas acima. Esta convenção ajuda os revisores a identificar ou localizar rapidamente as partes desta RFC cobertas por essas palavras-chave.

## 3. Título da seção 2 conforme apropriado

>Uma requisição feita a partir do cliente em direção ao servidor desejado deve possuir o determinado formato:
<metodo> <arquivo desejado + extensão> <versão do HTTP>
HOST: <url do host>
GPOS: <nome do dispositivo>

A exemplo:

GET index.html HTTP/1.1 HOST: www.ufs.br <longitude> <latitude> <altitude>
HOST: www.ufs.br
GPOS: gps

O servidor, por sua vez, deve retornar uma resposta no seguinte formato:

HTTP/1.1 nome_dispositivo ttl class GPOS longitude latitude altitude

## 4. Considerações de segurança

> Adicione considerações de segurança

## 5. Considerações da IANA

> Adicione quaisquer considerações da IANA

## 6. conclusões
> Adicione quaisquer conclusões

## 7. Referências

### 7.1. Referências normativas

[1]	Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels", BCP 14, RFC 2119, March 1997.

[2]	Crocker, D. and Overell, P.(Editors), "Augmented BNF for Syntax Specifications: ABNF", RFC 2234, Internet Mail Consortium and 
Demon Internet Ltd., November 1997.

[RFC2119]	Bradner, S., "Key words for use in RFCs to Indicate Requirement Levels", BCP 14, RFC 2119, March 1997.

[RFC2234]	Crocker, D. and Overell, P.(Editors), "Augmented BNF for Syntax Specifications: ABNF", RFC 2234, Internet Mail 
Consortium and Demon Internet Ltd., November 1997.

[RFC1712]  Baldoni, D., "DNS Encoding of Geographical Location", RFC 1712, Curtin University of Technology,                      November 1994


                 

### 7.2. Informative References

[3]	Faber, T., Touch, J. and W. Yue, "The TIME-WAIT state in TCP and Its Effect on Busy Servers", Proc. Infocom 1999 pp. 1573-1583.
[Fab1999]	Faber, T., Touch, J. and W. Yue, "The TIME-WAIT state in TCP and Its Effect on Busy Servers", Proc. Infocom 1999  
pp. 1573-1583.

## 8. Acknowledgments
>Add any acknowledgements

