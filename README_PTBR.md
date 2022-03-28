# Pacote de redução de gráficos para FiveM
Pacote criado para melhorar o desempenho do FiveM no meu computador, verifique as configurações no leia-me do projeto


## Recursos
- Temas escuros e claros
- Pré-visualização em tempo real
- Modo tela cheia
- Multiplataforma


## Roteiro
**v0.1 - Alfa**
```diff
    + Diminuição do alcance do reflexo das sirenes da polícia em 20%;
```
**v0.2 - Alfa**
```diff
    + Removida a distância do reflexo das sirenes da polícia;
    + Removido 40% da emissão de luz de objetos estacionários;
```
**v0.3 - Alfa**
```diff
    + Removida a luz especular do sol e da lua;
    + Reduzida a distância que a sombra dos objetos será renderizada em 40%;
    + Opacidade da sombra reduzida em 85% (na configuração normal do GTAV)
```
**v0.4 - Alfa**
```diff
    + Fumaça completamente removida dos pneus durante a queima;
    + Reduzido o multiplicador de respingos de sangue em 90% durante o combate;
    + Removidas marcas de bala nas paredes (se quiser mantê-la, exclua os arquivos "decals_cs.dat" e "decals.dat"
```
**v0.5 - Beta**
```diff
    + Emissão de luz por objetos fixada em 75%;
    + Diminuição do alcance do reflexo das sirenes da polícia em 70%;
    + Removido mais 45% da emissão de luz de objetos estacionários;
    + Redução em 10% da fumaça do escapamento do veículo quando parado (se quiser voltar ao original, exclua os arquivos "vehicles.meta");
    + Removidos efeitos de reflexo de lente desnecessários (se quiser voltar ao original, exclua os arquivos "lensflare_f.xml", "lensflare_m.xml" e "lensflare_t.xml");
```
## Capturas de tela
![Captura de tela do aplicativo](https://via.placeholder.com/468x300?text=App+Captura de tela+Aqui)

## Instalação
### **Instalação básica**
- Extraia os arquivos do pacote para uma pasta na sua área de trabalho;
- Limpe completamente o cache do FiveM (script anexado);
- Faça um backup completo da pasta `citizen` do seu FiveM na pasta `%LocalAppData%\FiveM\FiveM.app\`;
- Faça um backup do arquivo `fivem.cfg` na pasta `%AppData%\FRoaming\CitizenFX\`;
- Faça um backup do arquivo `gta5_settings.xml` na pasta `%AppData%\FRoaming\CitizenFX\`;
- Abra o arquivo `gta5_settings.xml` e anote em um bloco de notas o valor da linha #72 - `VideoCardDescription`;
- Abra a pasta `%AppData%\FRoaming\CitizenFX\` e substitua o arquivo `gta5_settings.xml` pelo modificado;
- Edite o arquivo `gta5_settings.xml` com as informações salvas no passo #45;
- Abra a pasta `%AppData%\FRoaming\CitizenFX\` e substitua o arquivo `fivem.cfg` pelo modificado;
- Exclua completamente a pasta `citizen` original do seu FiveM e mova a atual no pacote;
- Mova o arquivo `a_CATUSSE_Package_VisualOptimisation_NG.rpf` para a pasta `%LocalAppData%\FiveM\FiveM.app\mods\`

### **Instalação complementar**
***Observação: As modificações a seguir são pessoais e podem ter desempenho diferente em cada computador, é recomendável fazer backup do computador antes de executar os arquivos.***

- **Disable Power Throttling**: Cria um novo plano de energia "forçando" seu computador a executar o FiveM com potência máxima de processamento;
- **Aumentar o desempenho da CPU**: Ativa o modo de jogo e define os jogos para serem executados com prioridade máxima em seu computador, substituindo outros programas;
- **Aumentar a capacidade de resposta do sistema**: Desativa a entrada de velocidade de rede moderada para que você possa parar de perder alguns pacotes (reduz o PL) durante o jogo;
- **KeyBoard Optimization**: Habilita o Keyboard Class Driver no Windows 10, um driver de dispositivo de kernel capaz de reduzir o tempo de resposta do teclado em alguns milissegundos (se o computador usar > entradas PS/2);
- **Mouse Optimization**: Habilita o Mouse Class Driver no Windows 10, um driver de dispositivo de kernel capaz de reduzir o tempo de resposta do mouse em alguns milissegundos (se o computador usar entradas PS/2);
## Créditos aos criadores
as presentes da internet nesse longo pacote foram todas as semanas (principalmente de sites estrangeiros) e editados mim durante longos períodos; caso decida compartilhe em outro site os créditos e informe o link original deste dê.

```diff
+ Rockstar Games, Inc: Preciso dizer alguma coisa?
+ LMF' Tah FiveM: Otimização Visual do Pacote
+ Nevek: Editor de Registro do Windows
```
## Suporte
Qualquer problema com travamento ou perda de FPS, entre em contato comigo pelo Ticket no [Discord](https://discord.gg/qCF9AbFDq5) do canal.

## Licença
[MIT](https://github.com/ricardo-codes/Graphics-Reduction-Pack-for-FiveM/blob/183aa1e35f59bc11f9df9c434236a02c26d77e81/LICENSE)
