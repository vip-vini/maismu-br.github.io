# Formatando o equipamento

![incluindo-imagem](maismu-br/maismu-br.github.io/docs/assets/images/manuais-procedimentos.jpg)

## Introdução

De maneira geral, formatar o PC com um sistema operacional como o Windows é um jeito de renovar completamente o sistema operacional e devido a este motivo, o procedimento é indicado como solução de diversos problemas em desktops e notebooks.

A formatação contribui na eficiência e na performance da sua máquina durante seu uso, além de acabar com aqueles programas difíceis de desinstalar como barras de navegador e eventuais vírus e pragas virtuais que poderiam estarem escondidos contribuindo e sendo prejudicial ao desempenho e eficiência do equipamento.

Não existe um tempo recomendado, ideal ou padronizado para que seja realizada a formatação e/ou reinstalação do Windows no PC, pois tal procedimento deve ser empregado como sendo o último recurso na resolução de problemas, este atrelado à baixa performance e/ou à uma constante instabilidade na execução do sistema operacional.

A verificação necessária antes da formatação em si é atentar-se às principais configurações da máquina antes de realizar a formatação. Por exemplo, a configuração de rede e vídeo, a verificação de quais softwares estão instalados na máquina para saber se será possível realizar a reinstalação após a formatação, bem como realizar o procedimento de backup de todos os arquivos e dados necessários, para só então realizar a formatação do sistema, apagando todos os dados do equipamento neste procedimento.

## Pré-requisitos para a formatação de equipamentos
### 1. Pré-requisito: Windows 10/11 _Professional_ e vantagens

* Atualizações de segurança regulares e automatizadas;
* Compatilhamento de arquivos com a utilização do OneDrive;
* Sinergia entre sistema operacional com o uso do _Office_ 365;
* Integração completa com _Azure_;
* Recursos ativos de segurança e proteção de dados;
* Gerenciamento de dispositivos móveis;
* Loja de aplicativos personalizada para a empresa;
* Implantação/instalação ágil e simplificada.

!!! note warning "Principal vantagem da utilização/aquisição do **&rarr;** Windows 10/11 versão _Professional_"
        
        A única e principal vantagem da utilização e da aquisição de licenças do **Windows 10/11 em sua versão _Professional_** em nossa empresa, é que somente com a aquisição desta consegue ingressar-se com êxito no domínio da empresa, pois as demais versões (inferiores) não detém/dispõem pela Microsoft esta funcionalidade técnica relacionado ao ingresso em domínios no geral.

### 2. Pré-requisito: Criptografia em repouso

* De fundamental importância, como citado em [Padrão Utilizado](../requisitos/#criptografia-em-repouso), preparar o equipamento com a criptografia em repouso torna-se imprescindível na formatação dos equipamentos.

### 3. Pré-requisito: Utilização de SSD's
*  É de grande utilidade e se faz necessário à empresa fazer a instalação de SSD's _(Solid State Drive)_ em todos os equipamentos por questões de padronização e pelas claras vantagens técnicas (memória _flash_ de armazenamento não volátil, alta velocidade de transferência de dados e principalmente pela eficiência/eficácia na inicialização dos sistemas operacionais) ante aos antigos HD's mecânicos.

### 4. Pré-requisito: Obtenção da imagem do Windows (ISO)
* Baixe a ferramenta [_MediaCreationTool22H2.exe_](https://go.microsoft.com/fwlink/?LinkId=691209) no [site oficial da Microsoft](https://www.microsoft.com/pt-br/software-download/windows10){:target='_blank"};
* Passo a passo para obtenção da ISO:
  
      **1.** Execute o **_MediaCreationTool22H2.exe_** conforme imagem abaixo:

      ![Formatação](../assets/images/media1.PNG#centershadow){width="80%"}

      **2.** Leia e aceite os termos de licença, em seguida clique em **Aceitar** conforme imagem abaixo:

      ![Formatação](../assets/images/media3.PNG#centershadow){width="80%"}

      **3.** Selecione a opção **"Criar mídia de instalação..."** e clique em **Avançar** conforme imagem abaixo:

      ![Formatação](../assets/images/media5.PNG#centershadow){width="80%"}

      **4.** Desmarque a caixa **"Usar as opções..."** e clique em **Avançar** conforme imagem abaixo:

      ![Formatação](../assets/images/media7.PNG#centershadow){width="80%"}

      **5.** Selecione a opção **Arquivo ISO** e clique em **Avançar** conforme imagem abaixo:

      ![Formatação](../assets/images/media8.PNG#centershadow){width="80%"}

      **6.** Escolha um diretório e clique em **Salvar** conforme imagem abaixo:

      ![Formatação](../assets/images/media9.PNG#centershadow){width="80%"}

      **7.** Após o término deste processo, clique em  **Concluir**:

      ![Formatação](../assets/images/media10.PNG#centershadow){width="80%"}

      **8.** A ISO **Windows** já estará criada no diretório conforme imagem abaixo:

      ![Formatação](../assets/images/media11.PNG#centershadow){width="80%"}

!!! note tip "Observação"
        
        Em caso de dúvidas no uso do executável para realizar o download da ISO, [clique aqui](https://support.microsoft.com/pt-br/windows/criar-m%C3%ADdia-de-instala%C3%A7%C3%A3o-para-o-windows-99a58364-8c02-206f-aa6f-40c3b507420d){:target='_blank"} para maiores informações e detalhes técnicos. 
      
### 5. Pré-requisito: Utilização de Pendrive com ISO Windows para a formatação
* _**Ventoy**_ é um software de código aberto que permite criar um pendrive bootável com vários sistemas operacionais ISO. Ele é capaz de suportar mais de 550 arquivos ISO diferentes e pode ser executado em sistemas Windows e Linux;
* Para configurar e preparar um pendrive para a inserção da ISO, segue-se o **passo a passo:** 
  
    **1.** Baixe o _Ventoy_ no [site oficial](https://www.ventoy.net/en/download){:target='_blank"} e instale-o no computador;

    **2.** Conecte o pendrive que deseja utlizar e abra o software _Ventoy_;

    **3.** Selecione o pendrive na lista de dispositivos disponíveis;

    **4.** Clique em _"Install"_ para instalar o _Ventoy_ no pendrive;
    
    **5.** Copie o (os) arquivo (os) ISO **Windows** que deseja usar para a raíz do pendrive;

    **6.** Ejete o pendrive com segurança e já preparado para realizar a formatação.

    **7.** Em caso de dúvidas acerca da preparação do pendrive, abaixo segue um tutorial:

<div style="text-align:center;">
    <iframe class="embed-video youtube lazyload"
            src="https://www.youtube.com/embed/watch?v=k7-wWXz078Y"
            title="YouTube video player"
            frameborder="0"
            width="640" height="360"
            allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture"
            allowfullscreen></iframe>
</div>

### 6. Licença
Licencimento por volume, não utilizar chaves de ativação (ativado por GPO / rede)

!!! note warning "Importante"
        
        **Aviso:** Não utilizar chaves ou outros métodos de autenticação na empresa.

## Instalando o Windows 10/11 Professional

### 1. Limpando o disco com a ferramenta **diskpart**
1. na tela inicial digite: ++ctrl+f10++
2. Digite: **diskpart**
      
      **a.** Digite: **list disk**

      **b.** Selecione o disco que deseja limpar: **select disk << numero >>**

      **c.** Digite: **clean**

      **d.** Feche a tela do **MSDOS** e volte à instalação do Windows

!!! note tip "Observação"
        
        Para nós colaboradores e técnicos do departamento de TI da empresa, não há uma necessidade expressa de um passo a passo detalhado de instalação do sistema operacional Windows 10/11, em específico atrelado à interface gráfica de instalação, até porque o processo de instalação é extremamente intuititvo.

### 2. Ingressar no dominio da empresa
Renomear o PC no padrão

### 3. Instalando programas (padrão)
No ambiente corporativo algumas ferramentas estão pré-selecionadas para serem instaladas em todos os computadores da empresa, abaixo uma lista dos [softwares homologados](../suporte/softwares.md)

1. Microsoft Teams (gpo)
2. [Notepad++ (ninite)](ninite.md)
3. [Microsoft Office 365 (manual)](../office365/instalacao.md)
4. [Inventário (gpo)](inventario.md)

## Configurando o OneDrive

!!! note tip "Configuração Padrão do OneDrive"
        
        Clique [aqui](../office365/onedrive.md){:target="_blank"} para realizar a configuração do seu **OneDrive**.


## Instalando o Office 365

!!! note tip "Instalação do Microsoft Office 365"
        
        Clique [aqui](../office365/instalacao.md){:target="_blank"} para realizar a instalação do seu **Microsoft Office 365**.
