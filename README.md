# Meu Segundo Cérebro — KeepOS

## 1. Tema e objetivo

**Objetivo original:** criar um guia para configurar o KeepOS rapidamente.

Este projeto tem como finalidade organizar conhecimentos, orientações e materiais de apoio sobre o sistema operacional KeepOS, facilitando sua configuração e utilização.

## 2. Fontes utilizadas

Foram reunidos materiais no Google NotebookLM:

| Fonte | Tipo | Justificativa |
|---|---|---|
| ASUS Brasil — KeepOS | Site institucional | Informações fornecidas pela fabricante. |
| Debian — Manuais de usuários(as) | Documentação técnica | Referência para conhecimentos sobre o ambiente Linux. |
| Como mudar o idioma do Linux para português | Vídeo tutorial | Orientações práticas de personalização. |
| Como usar o Keep OS? Review completo no ASUS Vivobook Go 15 | Vídeo | Demonstração prática do sistema. |
| O que não te contam sobre o Keep-OS do Vivobook GO 15 | Vídeo | Relato de experiência e possíveis limitações. |

### Link da ASUS

https://www.asus.com/br/content/asus-keepos/

## 3. Diretriz de comportamento do NotebookLM

O NotebookLM foi utilizado com suas configurações padrão, sem a inclusão de instruções personalizadas de comportamento. O objetivo do projeto foi orientado pelo tema: criar um guia para configurar o KeepOS rapidamente.

## 4. Perguntas e respostas do NotebookLM

Nesta etapa, foram realizadas consultas ao NotebookLM sobre funcionalidades e configurações do sistema operacional KeepOS. As respostas foram elaboradas com base nos materiais adicionados ao notebook.

### 4.1. Como configurar o brilho da tela?

**Resposta do NotebookLM:**

No ASUS Vivobook Go 15 com KeepOS, que utiliza a interface Cinnamon no Debian 11, o brilho pode ser ajustado de duas maneiras:

1. **Teclas de atalho:** utilizar as teclas de função com o ícone de brilho, possivelmente em combinação com a tecla `Fn`.
2. **Configurações do sistema:** acessar o menu principal, entrar em Configurações do Sistema e procurar a opção Monitor ou Energia para ajustar o brilho pela barra deslizante.

**Fontes citadas:** [1], [4] e [5].

### 4.2. Como utilizar o GNOME?

**Resposta do NotebookLM:**

No KeepOS, baseado no Debian 11, os ambientes de trabalho GNOME e Cinnamon vêm pré-instalados, sendo o Cinnamon a interface padrão do sistema.

Entretanto, as fontes consultadas não apresentam instruções passo a passo detalhadas sobre o uso do GNOME. Os materiais abordam principalmente o Cinnamon, a alteração de temas, videoaulas offline disponíveis na pasta pessoal do usuário e manuais gerais do Debian.

**Fontes citadas:** [1], [2], [3], [4], [5], [6] e [7].

### 4.3. Como instalar o idioma português?

**Resposta do NotebookLM:**

Para instalar e alterar o idioma do Linux para português pelo terminal, foram apresentados os seguintes passos:

1. Abrir o terminal com `Ctrl + Alt + T`.
2. Instalar o pacote de idioma indicado.
3. Executar a reconfiguração dos pacotes de idiomas e localidades.
4. Selecionar português na lista de opções, confirmar e aguardar o processamento.
5. Reiniciar o computador para aplicar as alterações.

**Fonte citada:** [1].

### 4.4. Como ver as informações do sistema?

**Resposta do NotebookLM:**

O KeepOS permite consultar informações do computador pela interface gráfica ou pelo terminal.

**Pela interface gráfica:**

1. Abrir o menu principal.
2. Acessar Configurações do Sistema.
3. Selecionar Informações do Sistema, na seção de hardware e sistema.

Entre as informações apresentadas estão:

- Versão do Debian e do Cinnamon.
- Versão do Kernel Linux.
- Modelo do processador.
- Quantidade de memória RAM.
- Placa gráfica.
- Armazenamento SSD.

**Pelo terminal:**

Abrir o terminal com `Ctrl + Alt + T` e utilizar:

- `free -h`: consulta a memória RAM total e seu consumo.
- `top`: acompanha processos ativos e utilização do processador.

**Fontes citadas:** [1], [2], [3] e [4].

### 4.5. Como instalar atualizações do sistema e dos aplicativos instalados de fábrica?

**Resposta do NotebookLM:**

O KeepOS permite atualizar o sistema e os aplicativos de duas maneiras.

**Pela interface gráfica:**

- Utilizar a Loja de Aplicativos integrada para pesquisar, visualizar e atualizar programas.
- Consultar as videoaulas offline que acompanham o sistema, com orientações sobre conexão à internet e atualizações.

**Pelo terminal:**

Abrir o terminal com `Ctrl + Alt + T` e executar:

```bash
sudo apt update
```

Esse comando atualiza a lista de programas disponíveis nos repositórios.

Em seguida, executar:

```bash
sudo apt upgrade
```

Esse comando aplica as atualizações disponíveis para os pacotes instalados.

**Observação:** segundo as fontes consultadas, o KeepOS é baseado no Debian 11 e utiliza repositórios Debian e repositórios próprios de personalização. Podem ocorrer instabilidades no servidor próprio, afetando algumas atualizações.

**Fontes citadas:** [1], [2], [3], [4], [5], [6], [7] e [8].

### 4.6. Como descobrir a arquitetura do sistema operacional?

**Resposta do NotebookLM:**

No KeepOS e em distribuições baseadas no Debian, é possível identificar a arquitetura pela interface gráfica ou pelo terminal.

**Pela interface gráfica:**

1. Abrir o Menu Principal.
2. Acessar Configurações do Sistema.
3. Selecionar Informações do Sistema.

A resposta consultada informa que o processador AMD Ryzen 5 opera em 64 bits, com arquitetura x86_64/amd64.

**Pelo terminal:**

Abrir o terminal com `Ctrl + Alt + T` e utilizar um dos seguintes comandos:

- `uname -m`: exibe a arquitetura do kernel.
- `arch`: também exibe a arquitetura da máquina.
- `dpkg --print-architecture`: informa a arquitetura padrão para instalação de pacotes Debian.
- `lscpu`: apresenta informações detalhadas do processador e sua arquitetura.

**Fontes citadas:** [1], [2], [3], [5] e [6].

### 4.7. Como alterar o tema visual do sistema?

**Resposta do NotebookLM:**

No KeepOS, que utiliza a interface Cinnamon no Debian 11, a aparência pode ser personalizada pelas configurações do sistema.

1. Abrir o menu principal.
2. Acessar Configurações do Sistema.
3. Procurar a opção Temas ou Aparência.
4. Escolher os elementos visuais que deseja modificar.

É possível alterar elementos como ícones, bordas das janelas, controles e painel. O sistema disponibiliza opções de estilos e temas pré-instalados.

**Fontes citadas:** [1], [2], [3] e [4].

### 4.8. Como conectar à rede Wi-Fi?

**Resposta do NotebookLM:**

Para conectar o ASUS Vivobook Go 15 com KeepOS à rede Wi-Fi, foram apresentadas duas possibilidades.

**Pela barra de tarefas:**

1. Clicar no ícone de rede no canto inferior direito da tela.
2. Selecionar a rede Wi-Fi desejada.
3. Digitar a senha e confirmar a conexão.

**Pelas videoaulas offline:**

O sistema acompanha videoaulas salvas localmente na pasta pessoal do usuário. Entre elas, há uma aula sobre configuração e conexão à rede Wi-Fi.

**Observação sobre o hardware:** a resposta informa que o Vivobook Go 15 não possui porta física RJ45 e utiliza conectividade sem fio integrada.

**Fontes citadas:** [1], [2], [3] e [4].

### 4.9. Como criar e acessar posteriormente novas pastas?

**Resposta do NotebookLM:**

No KeepOS, é possível criar e organizar pastas pela interface gráfica ou pelo terminal.

**Pela interface gráfica:**

1. Clicar com o botão direito em um espaço vazio da Área de Trabalho ou do Gerenciador de Arquivos.
2. Selecionar Criar Nova Pasta.
3. Digitar o nome desejado.
4. Pressionar Enter.

Também é possível utilizar o atalho `Ctrl + Shift + N` no Gerenciador de Arquivos.

Para acessar posteriormente, basta abrir a Pasta Pessoal e navegar até o local onde a pasta foi salva.

**Pelo terminal:**

Abrir o terminal com `Ctrl + Alt + T`.

Para criar uma pasta, utilizar o comando:

```bash
mkdir MinhaPasta
```

Para acessar a pasta:

```bash
cd MinhaPasta
```

Para visualizar seu conteúdo:

```bash
ls
```

### 4.10. Materiais complementares gerados pelo NotebookLM

Além das respostas em texto, foram produzidos materiais complementares para facilitar o aprendizado e a consulta das informações.

- **Áudio gerado:** [Acessar arquivo de áudio](https://notebook.google.com/notebook/06511f90-ab8a-48a3-b944-0e5a41176fca/artifact/3a87ad53-474c-4807-8c34-acb00cd5d44d)
- **Mapa mental:** [Acessar mapa mental](https://notebook.google.com/notebook/06511f90-ab8a-48a3-b944-0e5a41176fca/artifact/1ed76d32-8f51-4bd7-a018-5960b0d6c925)
- **Guia de configuração rápida:** [Acessar guia](https://notebook.google.com/notebook/06511f90-ab8a-48a3-b944-0e5a41176fca/artifact/3b0aa242-aaf4-4ceb-b978-315a329b89bb)

Os materiais complementares ampliam as possibilidades de consulta ao conteúdo reunido no segundo cérebro.

## 5. NotebookLM compartilhado

[Acessar meu segundo cérebro no NotebookLM](https://notebook.google.com/notebook/06511f90-ab8a-48a3-b944-0e5a41176fca)
