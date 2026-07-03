# Stable Diffusion Image Generator 🚀

Este projeto consiste em um script em Python para geração automatizada de imagens a partir de descrições textuais (*Text-to-Image*), utilizando o modelo pré-treinado **Stable Diffusion v1.5** através da biblioteca `diffusers` da Hugging Face. O script também calcula e exibe o tempo exato de processamento necessário para renderizar a imagem utilizando aceleração por hardware (GPU).

## 🛠️ Funcionalidades

* **Geração de Imagens via IA:** Criação de cenários complexos a partir de prompts de texto.
* **Aceleração por GPU:** Configurado para rodar em arquiteturas NVIDIA (CUDA) com precisão de ponto flutuante reduzida (`torch.float16`) para otimização de VRAM e processamento ágil.
* **Métricas de Tempo:** Monitoramento em tempo real do tempo de inferência da rede neural.
* **Salvamento e Exibição:** Exportação automática do resultado para um arquivo `output.png` e abertura imediata na tela do sistema operacional.
