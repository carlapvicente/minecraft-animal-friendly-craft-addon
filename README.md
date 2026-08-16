<div align="center">

<!-- Banner do projeto -->

<img src="docs/assets/banner.png" alt="Animal Friendly Craft Add-on" width="100%">

# 🐾 Animal Friendly Craft Add-on

**Alternativas de crafting amigáveis aos animais sem precisar machucá-los no Minecraft Bedrock.**

[🇧🇷 Português](README.md) • [🇺🇸 English](docs/README.en-US.md)

<!-- Badges -->

<!-- Adicionar posteriormente: versão, Minecraft Bedrock, licença, status etc. -->

</div>

---

## 🌱 Sobre

O **Animal Friendly Craft Add-on** adiciona alternativas de criação para obter materiais normalmente associados aos animais sem precisar machucá-los.

A proposta é preservar a experiência de sobrevivência do Minecraft, oferecendo novos caminhos de crafting que se integram aos itens vanilla sempre que possível.

---

## ✨ Recursos

Atualmente, o add-on inclui:

* 🧵 **Couro Sintético**

  * Criado utilizando recursos renováveis e acessíveis durante a sobrevivência.
  * Pode ser convertido em couro vanilla.
  * Compatível com receitas vanilla que utilizam couro.

<!-- Adicionar novos recursos conforme o projeto crescer. -->

---

## 📖 Documentação

A documentação detalhada de cada item está disponível na pasta [`docs/`](docs/).

### Itens disponíveis

| Item            | Descrição                                           | Documentação                                        |
| --------------- | --------------------------------------------------- | --------------------------------------------------- |
| Couro Sintético | Alternativa de crafting ao couro obtido de animais. | [Ver documentação](docs/items/synthetic-leather.md) |

---

## 📦 Instalação

<!-- Definir processo final de distribuição antes de preencher esta seção. -->

1. Baixe o arquivo `.mcaddon` da versão desejada.
2. Abra o arquivo para importá-lo no Minecraft Bedrock.
3. Ative o **Behavior Pack** e o **Resource Pack** no mundo.
4. Entre no mundo e utilize as novas receitas.

<!-- Adicionar link para Releases quando o primeiro release estiver publicado. -->

---

## 🌐 Idiomas

O add-on possui suporte para:

* 🇧🇷 Português Brasil (`pt_BR`)
* 🇺🇸 English (`en_US`)

A documentação principal do repositório está disponível em Português Brasil.

Para acessar a versão em inglês:

➡️ [English documentation](docs/README.en-US.md)

---

## 🛠️ Desenvolvimento

### Requisitos

<!-- Confirmar posteriormente versões mínimas/recomendadas. -->

* Node.js
* npm
* Minecraft Creator Tools

### Instalação das dependências

```bash
npm install
```

### Build

```bash
npm run build
```

### Gerar o `.mcaddon`

```bash
npm run mcaddon
```

### Validação

```bash
npx mct validate
```

> Durante a validação do projeto completo, o Minecraft Creator Tools analisa a estrutura da raiz do projeto. Arquivos que não pertencem aos packs podem exigir tratamento específico durante esse processo.

<!-- Podemos substituir esta observação quando definirmos o fluxo definitivo de validação. -->

---

## 📁 Estrutura do projeto

```text
minecraft-animal-friendly-craft-addon/
├── behavior_packs/
│   └── cpv_animal_friendly/
├── resource_packs/
│   └── cpv_animal_friendly/
├── docs/
│   ├── assets/
│   ├── items/
│   └── README.en-US.md
├── scripts/
├── README.md
├── package.json
└── tsconfig.json
```

---

## 📜 Licença

Este projeto é distribuído sob a [Licença MIT](LICENSE).

Para facilitar a leitura em português do Brasil, também disponibilizamos uma [tradução não oficial da Licença MIT](LICENSE.pt-BR.md).

Em caso de divergência de interpretação, o texto original em inglês presente no arquivo `LICENSE` prevalece.

---

## ⚠️ Aviso

Este projeto não é afiliado, patrocinado ou endossado pela Mojang Studios ou pela Microsoft.

Minecraft é uma marca registrada da Microsoft.

---

## 📚 Referências

- [Minecraft: Bedrock Edition Creator Documentation](https://learn.microsoft.com/en-us/minecraft/creator/)
- [Getting Started with Add-On Development](https://learn.microsoft.com/en-us/minecraft/creator/documents/gettingstarted)
- [MC Icons](https://mc-icons.com/) — fonte dos ícones vanilla utilizados na documentação.

---

<div align="center">

Feito com 🩷 para quem prefere construir, explorar e criar sem precisar machucar os bichinhos. 🐾

</div>
