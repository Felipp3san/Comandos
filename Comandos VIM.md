Comandos VIM 

        ↑
      ← h j k l →
          ↓

w - Move de palavra em palavra, considera caracteres especiais como outras palavras (,;({}))
W - Move de palavra em palavra, ignora caracteres especiais.
b - Move de palavra em palavra para trás, considera caracteres especiais como outras palavras (,;({}))
B - Move de palavra em palavra para trás, ignora caracteres especiais.

e - Move para o fim da palavra da frente, considera caracteres especiais.
E - Move para o fim da palavra da frente, não considera caracteres especiais.
ge - Move para o fim da palavra de trás, considera caracteres especiais como outras palavras.
gE - Move para o fim da palavra de trás, ignora caracteres especiais.

f(caractere) - Procura pela próxima ocorrência do caractere selecionado na mesma linha.
F(caractere) - Procura pela ocorrência anterior do caractere selecionado.
t(caractere) - Move para a posição anterior ao caractere selecionado.
T(caractere) - Move para a posição anterior ao caractere selecionado, ao contrário.

; - Após f(caractere), procura a ocorrência seguinte do mesmo caractere.
, - Após f(caractere), retorna para a ocorrência anterior do mesmo caractere.

0 - Move para o primeiro caractere da linha.
$ - Move para o último caractere da linha.
g_ - Move para o último caractere 'não em branco'. 
^ - Move para o primeiro caractere 'não em branco'.            

} - Move verticalmente saltando parágrafos para baixo.
{ - Move verticalmente saltando parágrafos para cima.
CTRL / D - Salta metade da página verticalmente para baixo.
CTRL / U - Salta metade da página verticalmente para cima. 

/(padrão) - Encontra todas as ocorrências seguintes do padrão de caracteres especificado.
?(padrão) - Encontra todas as ocorrências anteriores do padrão de caracteres especificado.

Utilize 'n' ou 'N' para se mover entre as ocorrências.
'n' para baixo e 'N' para trás.

Utilize números antes dos comandos para multiplicar os seus efeitos.
Por exemplo, 2w, pula duas palavras. 5k, salta 5 linhas para cima.


