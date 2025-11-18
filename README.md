# WriteSerialNumber / Gravar Número de Série
Uma ferramenta Windows desenvolvida em C# para gravar (definir) um número de série personalizado em máquinas Windows.

![NS](https://user-images.githubusercontent.com/47501385/194639214-2579ea32-36c3-4bdc-87ad-930eda8a520d.png)

## 🚀 Funcionalidades

- Interface gráfica (GUI) para digitar o número de série desejado.
- Escrita do número de série no sistema local ou em local configurável.
- Validação de entrada para garantir que o serial está no formato correto.
- Logs básicos para acompanhar operações de gravação.

## Tecnologias

- C# / .NET (versão usada no projeto)
- WinForms
- Classes .NET para acesso ao sistema (ex: WMI, se usado para gravar no hardware ou BIOS)

## Como usar

1. Clone o repositório:  
   ```bash
   git clone https://github.com/antonioedinadson/gravar-numero-serie.git
2. Abra a solução WriteSerialNumber.sln no Visual Studio.  
3. Compile e execute a aplicação.  
4. Insira o número de série desejado no campo apropriado da UI, e tecle enter.
5. Verifique o log (se houver) para confirmar que a operação foi bem-sucedida.  
