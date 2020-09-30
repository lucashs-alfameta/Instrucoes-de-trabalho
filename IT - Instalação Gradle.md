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

# IT - INSTAÇÃO GRADLE

## Tarefa: Instalação do Gradle

### **1. Resultado Esperado**

Ter o Gradle instalado e configurado.

----------
### **2. Responsabilidades**

Programador

----------
### **3. Material Necessário**

- Notebook
- Conexão com a internet
- Acesso administrador no sistema operacional
- OpenJDK ou JDK

----------
### **4. Observações / Informações Adicionais** 

----------
### **5. Descrição da Atividade**

**Passo 1:**

Faça o download da versão mais recente do Gradle. [Link para download](https://gradle.org/install/#manually).


**Passo 2**

Crie uma pasta chamada **Gradle** na raiz do disco local. Extraia o conteudo da pasta ***gradle-X.X.X*** para esta pasta recém criada.

**Passo 3**

Configure as variáveis de ambiente para que apontem ao SDK.
Vá para **Painel de controle** > **Sistema** > **Configurações avançadas do sistema**

![Variáveis de ambiente](imagens/variaveis-ambiente-windows.png)

Sob **Variáveis do sistema**, selecione ***Path***, clique em ***Editar*** e então em ***Procurar***.

Navegue até a pasta do Gradle, selecione a pasta ***bin*** e dê ***Ok***.

**Passo 4**

Configure as variáveis de ambiente para que apontem ao SDK.
Vá para **Painel de controle** > **Sistema** > **Configurações avançadas do sistema**

![Variáveis de ambiente](imagens/variaveis-ambiente-windows.png)

Sob **Variáveis de usuário**, clique em **Novo**

No nome da variável coloque ANDROID_SDK_ROOT.

E no valor coloque o caminho para o diretório do android `C:\Android`.