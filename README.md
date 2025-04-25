# resumo-lab-aula05
Este repositório contem as lições aprendidas durante o desenvolvimento do lab-DIO-AZURE

## Criar Máquina Virtual

![maquina-virtual01](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/maquina-virtual01.png)

![maquina-virtual02](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/maquina-virtual02.png)

![maquina-virtual03](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/maquina-virtual03.png)


É possível criar uma máquina virtual (VM) já preconfigurada, com base em uma solução definida pelo usuário, ou customizá-la conforme a necessidade.

#### Para criar uma VM, é necessário definir:

- Assinatura

- Grupo de recursos: Onde ficarão todos os recursos definidos pelo usuário.

- Região: Data center onde o recurso será armazenado.

- Zona de disponibilidade (opcional): É possível definir até 3 zonas de disponibilidade.
  
  Existe a opção de dimensionamento, que pode ser feito de forma manual ou automática.
  
  Isso permite configurar a quantidade de instâncias, limites, processamento, entre outros, o que reduz as chances de indisponibilidade e lentidão no tráfego.

- Tipo de segurança

- Imagem: Sistema operacional e configuração base da VM.

- Tamanho: Define a família de serviços, quantidade de CPU e memória disponíveis para a aplicação.

- Credenciais: Definir as credenciais de login.

- Regras de portas de entrada: Definir quais portas da rede poderão ser acessadas pela internet.

### Disco

![disco](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/disco.png)

- É definido o tamanho e o tipo de serviço de disco.

- Existe a opção de excluir o disco juntamente com a VM.

- É possível criar ou anexar um disco adicional.

### Rede

![rede](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/rede.png)

- Definir a rede virtual.

- Definir o IP.

- Existe a opção de excluir o IP juntamente com a rede virtual.

### Gerenciamento

![gerenciamento](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/gerenciamento.png)

- Possibilidade de inserir credenciais administrativas.

- Opção de desligamento automático personalizado.

- Possibilidade de habilitar backup.

### Monitoramento

![monitoramento](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/monitoramento.png)

- Opção de habilitar alertas.

- Opção de habilitar diagnósticos.

### Avançado

![avancado](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/avancado.png)

- Permite instalar extensões durante a execução.

- Permite adicionar aplicativos à máquina virtual.

### Revisar + Criar

![revisar-criar](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/revisar-criar.png)

- Apresenta um resumo das configurações realizadas e o custo final do serviço.

## Área de Trabalho Virtual do Azure

![desktop](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/desktop-virtual.png)

Permite criar um desktop virtual e compartilhá-lo com outros usuários.

Para criar, é necessário definir:

- Assinatura

- Localização

- Nome do pool de hosts

Além disso, existem dois tipos de pool de hosts:

- Pessoal: Criado e destinado a um único usuário.

- Em pool: Compartilhado por vários usuários.

Também é possível adicionar máquinas virtuais ao ambiente.

## Aplicativo de Funções (Function App)

![function-app](https://github.com/TiagoFerreirago/resumo-lab-aula05/blob/main/images/function.png)

Para criar um aplicativo de funções, é necessário:

- Definir o nome do aplicativo.
  
- Escolher a forma de implantação: por código ou imagem de contêiner.

- Configurar a pilha de runtime, de acordo com a linguagem e ambiente desejados.
