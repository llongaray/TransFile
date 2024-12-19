# TransFile

TransFile é um aplicativo versátil que permite a conversão de arquivos entre diferentes formatos, além de oferecer a visualização do espectro de áudio. Este aplicativo é ideal para usuários que precisam manipular arquivos de imagem, áudio, vídeo, documentos e planilhas de forma rápida e eficiente.

## Funcionalidades

### 1. Conversão de Arquivos
O TransFile permite a conversão de diversos tipos de arquivos, incluindo:

- **Imagens**: Converta imagens em formatos como JPG, PNG, GIF, BMP e TIFF. Além disso, você pode converter imagens em arquivos de áudio MP3, extraindo texto da imagem usando OCR (Reconhecimento Óptico de Caracteres).
  
- **Áudio**: Converta arquivos de áudio entre formatos como MP3, WAV, AAC e FLAC.

- **Vídeo**: Converta vídeos em formatos como MP4, AVI, MKV e MOV.

- **Documentos**: Converta documentos em formatos como PDF, DOCX e TXT.

- **Planilhas**: Converta arquivos de planilhas em formatos como XLSX e CSV.

### 2. Visualização do Espectro de Áudio
Após a conversão de arquivos de áudio, você pode visualizar o espectro do áudio gerado. Isso é útil para análise de frequência e para entender melhor as características do áudio.

## Como Usar

### Passo a Passo

1. **Iniciar o Aplicativo**: Execute o aplicativo TransFile em seu terminal ou ambiente de desenvolvimento.

2. **Escolher o Tipo de Arquivo**: O aplicativo apresentará um menu onde você poderá escolher o tipo de arquivo que deseja converter ou visualizar.

3. **Selecionar a Conversão**:
   - Se você escolher "Imagem", "Áudio", "Vídeo", "Documento" ou "Planilha", será solicitado que você insira o caminho do arquivo a ser convertido.
   - Em seguida, escolha a extensão para a qual deseja converter o arquivo.
   - Informe o caminho da pasta onde o arquivo convertido será salvo.

4. **Converter Múltiplos Arquivos**: Se você deseja converter vários arquivos de uma vez, escolha a opção "Múltiplos" e siga as instruções para selecionar a pasta de origem e a extensão de destino.

5. **Visualizar o Espectro de Áudio**: Se você deseja visualizar o espectro de um arquivo de áudio, escolha a opção "Visualizar Espectro" e insira o caminho do arquivo de áudio. O espectro será exibido em uma nova janela.

### Dicas

- Certifique-se de que os caminhos dos arquivos e pastas estejam corretos para evitar erros durante a conversão.
- Para a conversão de imagens em áudio, o aplicativo utiliza OCR para extrair texto. A qualidade do texto extraído pode variar dependendo da clareza da imagem.

## Requisitos

- Python 3.x
- Bibliotecas necessárias: `soundfile`, `audioread`, `Pillow`, `opencv-python`, `gtts`, `pytesseract`, `InquirerPy`, `rich`, `matplotlib`, `numpy`, `librosa`.

## Conclusão

TransFile é uma ferramenta poderosa para quem precisa manipular diferentes tipos de arquivos de forma prática e eficiente. Com suas funcionalidades de conversão e visualização de espectro, ele se torna um recurso valioso para usuários em diversas áreas.
