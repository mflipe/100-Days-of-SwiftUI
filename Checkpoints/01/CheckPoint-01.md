# CheckPoint 01

Você já sabe o suficiente para começar a escrever seu primeiro código útil, embora bastante simples: vamos converter temperaturas de Celsius para Fahrenheit.

Seu objetivo é escrever um playground Swift que:

1. Cria uma constante mantendo qualquer temperatura em Celsius.
2. Converte em Fahrenheit multiplicando por 9, dividindo por 5 e, em seguida, adicionando 32.
3. Imprime o resultado para o usuário, mostrando os valores Celsius e Fahrenheit.

Você já sabe tudo que precisa para resolver esse problema, mas se quiser algumas dicas, vou adicionar algumas abaixo.

Hacking com assinantes Swift + pode obter uma solução de vídeo completa para este ponto de verificação aqui: Solução para o ponto de verificação 1. Se você ainda não se inscreveu, você pode começar um teste gratuito hoje.

Nota: Eu realmente encorajo você a tentar construir este playground antes de ler qualquer dica ou tentar minha solução. Eu sei que pode parecer simples, mas o curso começa a ficar mais difícil logo e é importante ter certeza de que você aprendeu todos os fundamentos.

Vá em frente e tente construir o playground agora.

Ainda aqui? Ok, aqui estão algumas dicas:

1. Use `let` para declarar sua constante. Você pode chamá-la do que quiser, mas acho que `celsius` seria um nome apropriado.
2. `Celsius` é normalmente armazenado como um `decimal`, portanto, certifique-se de criá-lo como um. Isso pode significar adicionar `“.0”` ao final - usando `25,0` em vez de `25`, por exemplo. 
3. Usamos `*` para multiplicação e `/` para divisão.
4. Use `\(someVariable)` para ativar a interpolação de strings.
5. Se você quiser se divertir com `print()`, pode usar `Option + Shift + 8` para obter o símbolo de graus: `°`. Isso significa que você pode escrever algo como `25 °F`.
