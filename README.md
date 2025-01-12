# Assistente Virtual com Reconhecimento de Voz

Este projeto implementa um assistente virtual que utiliza bibliotecas de Processamento de Linguagem Natural (PLN) para reconhecimento de voz e conversão de texto em áudio. O sistema foi ajustado para funcionar no Google Colab sem a necessidade de usar microfone diretamente, utilizando arquivos de áudio para entrada de comandos.

## 🛠 Funcionalidades
- **Text to Speech (TTS)**: Conversão de texto em áudio usando a biblioteca `gTTS`.
- **Speech to Text (STT)**: Reconhecimento de fala a partir de arquivos de áudio `.wav` usando a biblioteca `SpeechRecognition`.
- **Automação de Comandos**: Executa comandos como abrir o Google e realizar pesquisas.

## 📋 Requisitos
O código foi ajustado para ser executado no **Google Colab**, portanto, não é necessário instalar nada localmente. As bibliotecas necessárias são instaladas diretamente no notebook.

### Bibliotecas Utilizadas
- `gTTS`: Para conversão de texto em fala.
- `SpeechRecognition`: Para reconhecimento de fala a partir de arquivos de áudio.
- `PyDub`: Para manipulação de áudio.
- `IPython.display.Audio`: Para reproduzir áudio no Colab.

## 🚀 Como Executar no Google Colab

### 1️⃣ Passo 1: Instale as Dependências
No início do notebook, execute o seguinte código para instalar as bibliotecas necessárias:

```python
!apt-get install espeak
!pip install gTTS SpeechRecognition PyDub
```

### 2️⃣ Passo 2: Execute o Código Principal
Copie o código principal do assistente virtual e cole no seu notebook do Google Colab.

### 3️⃣ Passo 3: Faça Upload de um Arquivo de Áudio
Quando solicitado, faça o upload de um arquivo de áudio no formato `.wav`. O assistente irá transcrever o conteúdo do áudio e executar comandos com base no que foi dito.

### Exemplo de Comandos Reconhecidos
- "Abrir Google"
- "Pesquisar por inteligência artificial"
- "Abrir cmd"

## 🎤 Como Criar um Arquivo de Áudio `.wav`
1. Use o **Gravador de Voz** no Windows.
2. Use o **QuickTime Player** no macOS.
3. Utilize aplicativos de gravação em smartphones.
4. Salve o arquivo no formato `.wav`.

## 🧪 Teste no Colab
1. Execute o notebook no Colab.
2. Faça o upload do arquivo de áudio.
3. Ouça a resposta do assistente.

## 📚 Referências
- [gTTS Documentation](https://gtts.readthedocs.io/en/latest/)
- [SpeechRecognition Documentation](https://pypi.org/project/SpeechRecognition/)

## 📝 Observações
- Certifique-se de que o arquivo de áudio está claro e nítido para melhorar o reconhecimento de voz.
- O Colab não suporta captura de áudio diretamente pelo microfone, por isso a necessidade de usar arquivos `.wav`.
