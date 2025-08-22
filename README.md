
# Mtxucro Extractor Strings

uma ferramenta em C++ para extrair informações de arquivos executáveis (.exe). Ela calcula o hash MD5, mostra o nome, o tamanho do arquivo e ainda dá detalhes sobre o tempo de criação. Foi feita para ajudar a entender melhor arquivos PE, aqueles usados no Windows.

## Funcionalidades:
- Cálculo do hash MD5 de arquivos para integridade e verificação.
- Extração de Strings de arquivos binários, com destaque para informações como o nome do arquivo e o tamanho.
- Conversão de timestamps binários para formato legível.
- Exibe informações detalhadas sobre o arquivo, como seu nome, hash MD5, tamanho e timestamp.

## Requisitos:
- Windows (por causa do uso da API SetConsoleTitle do Windows).
- Compilador C++ (como o Visual Studio ou MinGW).

## Como Usar:
1. Baixe ou clone o repositório.
2. Compile o código utilizando um compilador C++.
3. Execute o programa e forneça o caminho para um arquivo .exe para obter as informações extraídas.

## Dependências:
- Nenhuma biblioteca externa além das padrão do C++.

## Exemplo de Saída:
Enter the path to the .exe file: C:/path/to/file.exe

File Name: file

File Size: 1234567 bytes

MD5: 098f6bcd4621d373cade4e832627b4f6

PcaSvc: 0x1000

DPS: !2023/08/22:15:00:00
