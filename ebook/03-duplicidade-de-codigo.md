**Bancada Viva — cinco hábitos para programar com IA**

# Duplicidade de código

Uma regra mora num lugar. Se a mesma decisão aparece em dois arquivos, você terá dois futuros. Um muda. O outro esquece. O bug nasce no vão entre as cópias.

A IA duplica quando o pedido é vago. "Faça o mesmo nos outros módulos" vira cópia colada. "Valide o e-mail aqui também" vira uma segunda função com outro nome. O modelo não sente o custo de manter as duas. Quem sente é você, na semana seguinte.

O hábito cabe numa frase. Aponte a fonte única e peça referências, não cópias. Se a regra ainda não tem casa, peça a casa primeiro. Depois peça aos outros pontos que a usem.

Na bancada: antes de aceitar o diff, procure a mesma condição escrita duas vezes. Se achar, devolva o pedido.

## Prompt para colar

```text
Esta regra já vive em [arquivo e função]. Não a copie.
Nos pontos que listei, chame essa fonte. Não crie uma segunda versão
com outro nome. Se faltar um lugar único para a regra, proponha esse
lugar primeiro e pare. Não espalhe a lógica enquanto a fonte não existir.
```

## Prompt de imagem (Gemini)

Ilustração editorial em guache e tinta sobre papel quente. Bancada de madeira sob luz âmbar. Cinco carimbos de madeira idênticos alinhados. Uma mão afasta quatro para a lateral e deixa um único carimbo no centro, sob a luz. Sem letras, sem logos, sem marca d'água, sem texto legível nos carimbos. Retrato 3:4. Evite rosto fotográfico de pessoa real e evite tela de computador com código.
