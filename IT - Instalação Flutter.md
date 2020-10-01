<table border="1">
    <tr>
        <th><img width="75" src="imagens/path41.png"></th>
        <th colspan=3>INSTRUÇÃO DE TRABALHO</th>
    </tr>
    <tr>
        <th>Código</th>
        <th>Data Elaboração</th>
        <th>Data Revisão</th>
        <th>Versão</th>
    </tr>
    <tr style="text-align: center;">
        <td>ITINS-01-01-001</td>
        <td>28/09/2020</td>
        <td>28/09/2020</td>
        <td>1</td>
    </tr>
</table>

# IT - INSTAÇÃO ANDROID SDK

## Tarefa: Instalação do JDK

### **1. Resultado Esperado**

Ter o Flutter instalado e configurado para desenvolvimento mobile e web.

----------
### **2. Responsabilidades**

Programador

----------
### **3. Material Necessário**

- Notebook
- Conexão com a internet
- Acesso administrador no sistema operacional
- Android SDK
- Gradle

----------
### **4. Observações / Informações Adicionais** 

----------
### **5. Descrição da Atividade**

#### **Passo 1: Download**

Faça o download da versão mais recente do Flutter no ***Beta channel***. [Link para download](https://flutter.dev/docs/development/tools/sdk/releases).

#### **Passo 2: Instalar**

Crie uma pasta chamada **Flutter** na raiz do disco local e faça a extração conteúdo da pasta **flutter** do arquivo compactado para dentro dela.

#### **Passo 3: Variáveis**

Para configurar as variáveis do sistema, vá para **Painel de controle** > **Sistema** > **Configurações avançadas do sistema** > **Avançado** > **Variáveis de Ambiente...**

![Variáveis de ambiente](imagens/variaveis-ambiente-windows.png)

Sob a seção **Variáveis do sistema**, selecione ***Path***, clique em ***Editar*** e então em ***Procurar***.<br>
Navegue até a pasta onde foi descompactado o Flutter, selecione a pasta ***bin*** e dê ***Ok*** em todas as janelas.

#### **Passo 4: Configurar**

Utilizando o ***PowerShell*** ou ***CMD*** aceite as licenças do SDK, para isso entre o comando:<br>
`flutter doctor --android-licenses`

Desative a coleta de estatísticas:<br>
`flutter config --no-analytics`

Ative o suporte web com o comando:<br>
`flutter config --enable-web`

Atualize os pacotes para que sejam compatíveis com a configuração web utilizando:<br>
`flutter update-packages`

#### **Passo 5: Plugins**

Com essas configurações é possível utilizar as seguintes ferramentas:

- Android Studio
- IntelliJ Community
- Visual Studio Code

Tanto o Android Studio quanto o IntelliJ oferecem um experiência de desenvolvimento mais integrada pois são IDEs completas, já o Visual Studio Code é um editor mais leve que ainda sim suporta a execução de debugação de app com Flutter.

Para o Android Studio e IntelliJ faça:

1. Abra as configurações dos plugins (**Configure > Plugins**)
2. Selecione o plugin **Flutter** e clique em ***Install***
3. Clique em sim quando for solicitado para instalar o plugin do Dart
4. Reinicie a IDE quando for solicitado

Para o Visual Studio Code:

1. Vá em **Extensions**
2. Pesquise por Flutter
3. Selecione na lista e instale
4. Também será instalado o plugin do Dart
5. Abra a Command Palette (**View > Command Palette**)
6. Digite doctor e selecione ***Flutter: Run Flutter Doctor***
7. Verifique o resultado.

----------
### Histórico de Revisões
<table border="1">
    <tr>
        <th>Versão</th>
        <th>Data</th>
        <th>Alteração</th>
        <th>Edição</th>
        <th>Revisão</th>
        <th>Aprovação</th>
    </tr>
    <tr style="text-align: center;">
        <td>1.0</td>
        <td>01/10/2020</td>
        <td>Versão Inicial</td>
        <td>Lucas</td>
        <td>-</td>
        <td>-</td>
    </tr>
</table>