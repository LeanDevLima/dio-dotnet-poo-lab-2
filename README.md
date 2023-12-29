# Digital Innovation One - Prática .NET

## Criando uma APP de cadastro em memória

Esse desafio é um projeto console para cadastro de séries, veio praticamente pronto, ao dar o comando 'dotnet run' foi possível ver o seguinte resultado:

```bash
$ dotnet run

DIO Séries a seu dispor!!!
Informe a opção desejada:
1- Listar séries
2- Inserir nova série
3- Atualizar série
4- Excluir série
5- Visualizar série
C- Limpar Tela
X- Sair

```

Então tomei a liberdade de fazer algumas alterações:

- **Cores no Console:** Adicionou-se cores ao console para tornar a interface mais atraente e legível.
- **Mensagens mais informativas:** Mensagens foram aprimoradas para fornecer informações mais claras ao usuário.
- **Tratamento de Erros:** Adicionou-se tratamento de erros para a entrada do usuário, evitando exceções não tratadas.
- **Console.Clear():** Adicionou-se um comando `Console.Clear()` para limpar a tela após cada escolha do usuário, proporcionando uma experiência mais limpa.
- **Console.Title:** Definiu-se um título para a janela do console para indicar o propósito do programa.

Essas são algumas práticas para melhorar a usabilidade e a estética do seu programa console. Ajuste conforme necessário para atender às suas preferências específicas. Esse foi o resultado:

<img src="terminal.png">

___

