# CS:GO Autoexec/scripts
## Quais arquivos estão neste repo?
* Configurações:
    * **autoexec**: executa todas as _cfgs_ no inicio do jogo.
    * **binds**: arquivo com todos os _alias_ e _binds_ usados.
    * **hud**: arquivo com todas as configurações de _HUD_.
    * **setings**: arquivo com algumas outras configurações.
    * **video**: arquivo com configurações de vídeo.
    

* Modos de jogo:
    * **bhop**: configura uma partida de _bhop_.
    * **surf**: configura uma partida de _surf skill_.
    * **awpmode**: configura uma partida de _awp_.
    * **training**: configura uma partida de treinamento.


## Como usar?

Para que todos os comandos/scripts funcionem, os arquivos devem ser colocados na pasta:
```
..\Steam\steamapps\common\Counter-Strike Global Offensive\csgo\cfg\
```

E deve ser colocado como opção de inicialização do *CSGO*:

```
+exec autoexec.cfg
```

Para definir as opções de inicialização, abra a biblioteca da Steam, clique com o botão direito no jogo e então vá em `Propriedades > DEFINIR OPÇÕES DE INICIALIZAÇÃO...` e então insira as opções desejadas.

### Modos de jogo
As *cfg* de modos de jogo devem ser colocadas na **mesma** pasta do arquivo `autoexec.cfg` e elas não serão executadas no inicio do jogo.

Para executa-las, foram criados alguns atalhos. Abra o console do jogo(Tecla `'`) e digite um dos comandos:

- **cfg**: apresenta um texto de ajuda.(_ainda não implementado_)
- **awp**: inicia o modo awp.
- **bhop**: inicia o modo bhop.
- **surf**: inicia o modo surf.
- **training**: inicia o modo de treinamento.

### Opções de vídeo
As opções de vídeo devem ser colocadas na pasta:

`..\Steam\userdata\16640487\730\local\cfg`

## Opções de inicialização
As minhas opções de inicialização são:

`+exec autoexec.cfg -novid -nojoy -freq 60 -refresh 60  -nod3d9ex -high -tickrate 128 -threads 8 +cl_forcepreload 1 -processheap +mat_queue_mode 2`

## Links hidratados:
https://steamcommunity.com/sharedfiles/filedetails/?l=portuguese&id=322206521
https://www.reddit.com/r/GlobalOffensive/comments/43nrni/fps_increase_tweak_commands/
