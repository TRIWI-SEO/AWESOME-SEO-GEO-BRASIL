# Dicionário de Dados: Lista Aberta de Recursos de SEO e GEO da TRIWI

Este dicionário descreve a base [recursos.csv](recursos.csv), a versão em dados da lista [Awesome SEO e GEO Brasil](../README.md): o que cada coluna significa, como o arquivo é formatado e como a base é mantida. A base está sob licença [CC BY 4.0](../LICENSE): o reuso é livre, inclusive comercial, desde que a TRIWI seja citada como fonte.

*Por equipe de SEO da TRIWI. Atualizado em 09/11/2026.*

## Quais bases existem?

| Arquivo | O que traz | Linhas |
|:---|:---|:---|
| [recursos.csv](recursos.csv) | Ferramentas, fontes oficiais e recursos de SEO e GEO, com categoria, descrição, endereço oficial, quem mantém, tipo de acesso e o recurso da TRIWI relacionado | 126 |

## Como abrir o arquivo?

O arquivo segue o mesmo padrão das outras bases abertas da TRIWI: codificação UTF-8, colunas separadas por vírgula, quebra de linha CRLF e datas no formato AAAA-MM-DD.

Se o Excel mostrar os acentos embaralhados, abra pelo menu Dados, opção De Texto/CSV, e escolha a codificação UTF-8.

## O que significa cada coluna?

| Coluna | Significado |
|:---|:---|
| nome | Nome do recurso como o dono o apresenta |
| categoria | Seção da lista: Recursos da TRIWI; Ferramentas de SEO; GEO e IAs; Fontes oficiais |
| subcategoria | Etapa ou tema dentro da seção, por exemplo Auditoria técnica e rastreamento |
| descricao | O que o recurso faz, em uma ou duas frases |
| url | Endereço oficial do recurso, sem link de afiliado e sem parâmetro de campanha |
| mantido_por | Empresa ou organização responsável pelo recurso |
| acesso | Gratuito, Gratuito com plano pago, Pago (ver abaixo) |
| recurso_triwi | Página da TRIWI que explica o tema ou faz o mesmo trabalho de graça; vazio quando o próprio recurso é da TRIWI |
| atualizado_em | Data da última revisão da linha |

## O que significa cada valor de acesso?

| Valor | Significado |
|:---|:---|
| Gratuito | Uso sem pagamento, com conta gratuita ou sem cadastro |
| Gratuito com plano pago | Uso gratuito real, com limite de volume ou de funções, e plano pago para quem precisa de mais |
| Pago | Sem uso gratuito permanente; teste gratuito por tempo limitado conta como pago |

O valor cobrado não entra na base: muda com frequência e envelhece a lista. O valor atualizado está sempre no site de cada recurso.

**Critério de contagem:** cada linha é um recurso com endereço próprio. Um produto dentro de outro, como o Ahrefs Webmaster Tools dentro da Ahrefs, conta como linha separada quando tem endereço e forma de acesso próprios. Serviços de agência e de consultoria não entram.

## Como a base é mantida?

A base é revisada pela equipe da TRIWI. Recurso descontinuado sai da base; recurso que mudou de endereço tem a linha corrigida e a data de revisão atualizada. Correções e sugestões chegam por [issue](../../../issues/new).
