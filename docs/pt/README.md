<div align="center">
  <img src="/docs/images/logo.png" alt="KrillinAI" height="90">

  # Ferramenta de Tradução e Dublagem de Vídeos AI de Implantação Minimalista

  <a href="https://trendshift.io/repositories/13360" target="_blank"><img src="https://trendshift.io/api/badge/repositories/13360" alt="krillinai%2FKrillinAI | Trendshift" style="width: 250px; height: 55px;" width="250" height="55"/></a>

  **[English](/README.md)｜[简体中文](/docs/zh/README.md)｜[日本語](/docs/jp/README.md)｜[한국어](/docs/kr/README.md)｜[Tiếng Việt](/docs/vi/README.md)｜[Français](/docs/fr/README.md)｜[Deutsch](/docs/de/README.md)｜[Español](/docs/es/README.md)｜[Português](/docs/pt/README.md)｜[Русский](/docs/rus/README.md)｜[اللغة العربية](/docs/ar/README.md)**

[![Twitter](https://img.shields.io/badge/Twitter-KrillinAI-orange?logo=twitter)](https://x.com/KrillinAI)
[![QQ 群](https://img.shields.io/badge/QQ%20群-754069680-green?logo=tencent-qq)](https://jq.qq.com/?_wv=1027&k=754069680)
[![Bilibili](https://img.shields.io/badge/dynamic/json?label=Bilibili&query=%24.data.follower&suffix=粉丝&url=https%3A%2F%2Fapi.bilibili.com%2Fx%2Frelation%2Fstat%3Fvmid%3D242124650&logo=bilibili&color=00A1D6&labelColor=FE7398&logoColor=FFFFFF)](https://space.bilibili.com/242124650)

</div>

### 📢 Nova versão para desktop win&mac lançada! Agradecemos seu feedback [a documentação está um pouco desatualizada, em constante atualização]

 ## Introdução ao Projeto  

Krillin AI é uma solução abrangente para localização e aprimoramento de áudio e vídeo. Esta ferramenta simples, mas poderosa, combina tradução de áudio e vídeo, dublagem e clonagem de voz, suportando formatos de saída em paisagem e retrato, garantindo uma apresentação perfeita em todas as principais plataformas (Bilibili, Xiaohongshu, Douyin, WeChat Video, Kuaishou, YouTube, TikTok, etc.). Com um fluxo de trabalho de ponta a ponta, o Krillin AI pode transformar materiais brutos em conteúdo pronto para uso em várias plataformas com apenas alguns cliques.

## Principais Características e Funcionalidades:
🎯 **Início com um clique**: Sem configurações de ambiente complexas, instalação automática de dependências, pronto para uso imediato, nova versão para desktop, mais conveniente!

📥 **Obtenção de Vídeo**: Suporta download via yt-dlp ou upload de arquivos locais

📜 **Reconhecimento Preciso**: Reconhecimento de voz de alta precisão baseado no Whisper

🧠 **Segmentação Inteligente**: Utiliza LLM para segmentação e alinhamento de legendas

🔄 **Substituição de Termos**: Substituição de vocabulário especializado com um clique 

🌍 **Tradução Profissional**: Tradução em nível de parágrafo baseada em LLM, mantendo a coerência semântica

🎙️ **Clonagem de Voz**: Oferece vozes selecionadas da CosyVoice ou clonagem de vozes personalizadas

🎬 **Composição de Vídeo**: Processamento automático de vídeos em paisagem e retrato e formatação de legendas


## Demonstração de Resultados
A imagem abaixo mostra o efeito do arquivo de legendas gerado após a importação de um vídeo local de 46 minutos, executado com um clique, sem ajustes manuais. Sem faltas, sobreposições, com pausas naturais e qualidade de tradução muito alta.
![Efeito de Alinhamento](/docs/images/alignment.png)

<table>
<tr>
<td width="33%">

### Tradução de Legendas
---
https://github.com/user-attachments/assets/bba1ac0a-fe6b-4947-b58d-ba99306d0339

</td>
<td width="33%">



### Dublagem
---
https://github.com/user-attachments/assets/0b32fad3-c3ad-4b6a-abf0-0865f0dd2385

</td>

<td width="33%">

### Retrato
---
https://github.com/user-attachments/assets/c2c7b528-0ef8-4ba9-b8ac-f9f92f6d4e71

</td>

</tr>
</table>

## 🔍 Suporte a Serviços de Reconhecimento de Voz
_**Todos os modelos locais na tabela abaixo suportam instalação automática de arquivos executáveis + arquivos de modelo, você só precisa escolher, o KrillinAI cuidará do resto.**_

| Fonte de Serviço        | Plataformas Suportadas | Opções de Modelo                             | Local/Nuvem | Observações          |
|--------------------|-----------------|----------------------------------------|-------|-------------|
| **OpenAI Whisper** | Todas as plataformas | -                                      | Nuvem    | Rápido e eficaz      |
| **FasterWhisper**  | Windows/Linux   | `tiny`/`medium`/`large-v2` (recomendado medium+) | Local    | Mais rápido, sem custos de nuvem |
| **WhisperKit**     | macOS (apenas para chips da série M) | `large-v2`                             | Local    | Otimização nativa para chips Apple |
| **WhisperCpp**     | Todas as plataformas | `large-v2`                             | Local    | Suporte para todas as plataformas       |
| **Alibaba Cloud ASR** | Todas as plataformas | -                                      | Nuvem    | Evitar problemas de rede na China continental  |

## 🚀 Suporte a Modelos de Linguagem Grande

✅ Compatível com todos os serviços de modelos de linguagem em nuvem/local que atendem às **especificações da API OpenAI**, incluindo, mas não se limitando a:
- OpenAI
- DeepSeek
- Tongyi Qianwen
- Modelos de código aberto implantados localmente
- Outros serviços de API compatíveis com o formato OpenAI

## Suporte a Idiomas
Idiomas de entrada suportados: Chinês, Inglês, Japonês, Alemão, Turco, Coreano, Russo, Malaio (em constante aumento)

Idiomas de tradução suportados: Inglês, Chinês, Russo, Espanhol, Francês e outros 101 idiomas

## Prévia da Interface
![Prévia da Interface](/docs/images/ui_desktop.png)


## 🚀 Começando Rápido
### Passos Básicos
Primeiro, baixe o arquivo executável correspondente ao seu sistema operacional na seção [Release](https://github.com/krillinai/KrillinAI/releases), siga o tutorial abaixo para escolher entre a versão desktop ou não desktop, e coloque em uma pasta vazia. Baixe o software em uma pasta vazia, pois após a execução, alguns diretórios serão gerados, e gerenciá-los em uma pasta vazia será mais fácil.  

【Se for a versão desktop, ou seja, o arquivo release que contém desktop, veja aqui】  
_A versão desktop é nova e foi lançada para resolver problemas de edição de arquivos de configuração para novos usuários, ainda há muitos bugs, em constante atualização_
1. Clique duas vezes no arquivo para começar a usar (a versão desktop também precisa de configuração, que deve ser feita dentro do software)

【Se for a versão não desktop, ou seja, o arquivo release que não contém desktop, veja aqui】  
_A versão não desktop é a versão inicial, a configuração é mais complexa, mas a funcionalidade é estável, adequada para implantação em servidores, pois fornecerá uma interface de usuário via web_
1. Crie uma pasta `config` dentro da pasta, e então crie um arquivo `config.toml` dentro da pasta `config`, copie o conteúdo do arquivo `config-example.toml` do diretório `config` e preencha com suas informações de configuração.
2. Clique duas vezes ou execute o arquivo executável no terminal para iniciar o serviço 
3. Abra o navegador e digite `http://127.0.0.1:8888` para começar a usar (substitua 8888 pela porta que você preencheu no arquivo de configuração)

### Para: Usuários de macOS
【Se for a versão desktop, ou seja, o arquivo release que contém desktop, veja aqui】  
Atualmente, devido a problemas de assinatura, a versão desktop não pode ser executada com um clique ou instalada via dmg, é necessário confiar manualmente no aplicativo, o método é o seguinte:
1. No terminal, abra o diretório onde o arquivo executável (supondo que o nome do arquivo seja KrillinAI_1.0.0_desktop_macOS_arm64) está localizado
2. Execute os seguintes comandos:
```
sudo xattr -cr ./KrillinAI_1.0.0_desktop_macOS_arm64
sudo chmod +x ./KrillinAI_1.0.0_desktop_macOS_arm64 
./KrillinAI_1.0.0_desktop_macOS_arm64
```

【Se for a versão não desktop, ou seja, o arquivo release que não contém desktop, veja aqui】  
Este software não foi assinado, portanto, ao executá-lo no macOS, após concluir a configuração dos arquivos na "etapa básica", você também precisará confiar manualmente no aplicativo, o método é o seguinte:
1. No terminal, abra o diretório onde o arquivo executável (supondo que o nome do arquivo seja KrillinAI_1.0.0_macOS_arm64) está localizado
2. Execute os seguintes comandos:
   ```
    sudo xattr -rd com.apple.quarantine ./KrillinAI_1.0.0_macOS_arm64
    sudo chmod +x ./KrillinAI_1.0.0_macOS_arm64
    ./KrillinAI_1.0.0_macOS_arm64
    ```
    Isso iniciará o serviço

### Implantação com Docker
Este projeto suporta implantação com Docker, consulte as [Instruções de Implantação com Docker](./docker.md)

### Instruções de Configuração de Cookies (opcional)

Se você encontrar problemas ao baixar vídeos

Consulte as [Instruções de Configuração de Cookies](./get_cookies.md) para configurar suas informações de cookies.

### Ajuda com Configuração (leia atentamente)
A maneira mais rápida e conveniente de configurar:
* Escolha `openai` para `transcription_provider` e `llm_provider`, assim você só precisa preencher `openai.apikey` nas três categorias de configuração abaixo: `openai`, `local_model`, `aliyun` para realizar a tradução de legendas. (`app.proxy`, `model` e `openai.base_url` podem ser preenchidos conforme sua situação)

Para usar o modelo de reconhecimento de linguagem local (não suportado no macOS), a configuração é a seguinte (equilibrando custo, velocidade e qualidade):
* Preencha `transcription_provider` com `fasterwhisper` e `llm_provider` com `openai`, assim você só precisa preencher `openai.apikey` e `local_model.faster_whisper` nas categorias de configuração abaixo: `openai`, `local_model` para realizar a tradução de legendas, o modelo local será baixado automaticamente. (`app.proxy` e `openai.base_url` conforme acima)

As seguintes situações exigem configuração do Alibaba Cloud:
* Se `llm_provider` for preenchido com `aliyun`, será necessário usar o serviço de modelo grande do Alibaba Cloud, portanto, é necessário preencher a configuração do item `aliyun.bailian`
* Se `transcription_provider` for preenchido com `aliyun`, ou se a função "dublagem" for ativada ao iniciar a tarefa, será necessário usar o serviço de voz do Alibaba Cloud, portanto, é necessário preencher a configuração do item `aliyun.speech`
* Se a função "dublagem" for ativada e um áudio local for enviado para clonagem de voz, será necessário usar o serviço de armazenamento em nuvem OSS do Alibaba Cloud, portanto, é necessário preencher a configuração do item `aliyun.oss`  
Ajuda para configuração do Alibaba Cloud: [Instruções de Configuração do Alibaba Cloud](./aliyun.md)

## Perguntas Frequentes

Por favor, consulte as [Perguntas Frequentes](./faq.md)

## Normas de Contribuição
1. Não envie arquivos desnecessários, como .vscode, .idea, etc., use .gitignore para filtrá-los
2. Não envie config.toml, mas sim use config-example.toml para enviar

## Contate-Nos
1. Junte-se ao nosso grupo QQ para esclarecer dúvidas: 754069680
2. Siga nossas contas de mídia social, [Bilibili](https://space.bilibili.com/242124650), compartilhando diariamente conteúdos de qualidade na área de tecnologia AI

## Histórico de Estrelas

[![Gráfico de Histórico de Estrelas](https://api.star-history.com/svg?repos=krillinai/KrillinAI&type=Date)](https://star-history.com/#krillinai/KrillinAI&Date)