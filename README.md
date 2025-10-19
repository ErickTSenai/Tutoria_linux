# Tutoria_linux
PROGRAMAÇÃO DE SISTEMAS EMBARCADOS LINUX

Descrição

Esta atividade tem como objetivo comparar dois ambientes distintos — Ubuntu Desktop e Buildroot (via QEMU) — com foco em sistemas embarcados. O trabalho envolve:

- Compilação cruzada de um programa simples em C (hello.c)
- Execução do binário em ambos os ambientes
- Coleta de métricas como uso de RAM, disco, número de processos e tempo de boot
- Análise crítica das diferenças observadas

Conteúdo da Entrega

-relatorio.pdf = Análise Ubuntu X Buildroot.pdf: Documento contendo a tabela comparativa entre os dois sistemas e uma análise crítica com mais de 500 palavras.

-codigo = hello.c: Código-fonte do programa “Hello World” utilizado para testes de compilação e execução.

-screenshots = Memorial descritivo Atividade 1: As capturas de tela dos comandos pedidos estão incorporadas na página 5 do memorial descritivo

Observações

- O binário foi compilado com o compilador cruzado `arm-buildroot-linux-gnueabihf-gcc` e embutido na imagem Buildroot.
- Durante os testes, foi necessário executar o binário no Buildroot usando o caminho absoluto (/hello_arm) em vez de ./hello_arm, devido à localização do arquivo na raiz do sistema.
- O sistema Buildroot foi executado com sucesso via QEMU, e todas as métricas foram coletadas conforme solicitado.
