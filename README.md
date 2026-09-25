<div align="center">

# 🕹️ Traplândia

<strong>Um jogo de plataforma 2D repleto de armadilhas, desenvolvido em Unity</strong>

<p>
  <img alt="Unity" src="https://img.shields.io/badge/Unity-000000?style=for-the-badge&logo=unity&logoColor=white" />
  <img alt="C#" src="https://img.shields.io/badge/C%23-239120?style=for-the-badge&logo=csharp&logoColor=white" />
</p>

<img alt="Licença MIT" src="https://img.shields.io/badge/Licença-MIT-2f855a?style=flat-square" />

</div>

---

## 🎮 Sobre o projeto

**Traplândia** é um jogo de plataforma 2D desenvolvido na engine **Unity**, com programação em **C#**. O jogador precisa avançar por fases repletas de obstáculos e armadilhas (*spikes*), testando reflexos e precisão de movimento a cada salto.

O projeto foi construído com arte em pixel art, usando **TextMesh Pro** para a interface e uma fonte pixelada personalizada (*Thaleah Pixel Font*), além do **Input System** da Unity para o controle do personagem.

## ✨ Destaques técnicos

- 🎨 Estética em **pixel art**, com tipografia dedicada via TextMesh Pro.
- 🕹️ Controles configurados através do **Unity Input System**.
- ⚠️ Sistema de armadilhas (*Spikes*) como principal mecânica de desafio.
- 🧩 Uso de **Prefabs** e **Materials** para reaproveitamento de elementos entre as fases.

## 📂 Estrutura do projeto

```text
TrapL-ndia/
├── Assets/
│   ├── Scenes/       # Fases e telas do jogo
│   ├── Scripts/       # Lógica de gameplay em C#
│   ├── Prefabs/        # Objetos reutilizáveis (personagem, armadilhas, etc.)
│   ├── Materials/       # Materiais e texturas
│   ├── Spikes/            # Armadilhas do jogo
│   ├── Settings/            # Configurações de renderização/URP
│   ├── TextMesh Pro/          # Recursos de UI/texto
│   └── Thaleah_PixelFont/       # Fonte pixelada personalizada
├── Packages/                      # Dependências do Unity Package Manager
├── ProjectSettings/                 # Configurações do projeto Unity
├── Projeto-2D-de-Plataforma.slnx       # Solução do projeto
└── LICENSE
```

## 🛠️ Como abrir o projeto

1. Instale o [Unity Hub](https://unity.com/download).
2. Instale a versão do Unity compatível com o projeto (recomenda-se a versão LTS mais recente).
3. Clone este repositório:
   ```bash
   git clone https://github.com/GehMay/TrapL-ndia.git
   ```
4. Abra a pasta do projeto pelo Unity Hub.
5. Pressione **Play** no editor para testar o jogo.

## 👩‍💻 Autoria

Desenvolvido por **Geovanna Tamagusko** ([@GehMay](https://github.com/GehMay)) como projeto de estudo em desenvolvimento de jogos.

## 📜 Licença

Este projeto está licenciado sob a licença **MIT** — veja o arquivo [LICENSE](LICENSE) para mais detalhes.
