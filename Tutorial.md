***

# 📖 Guia de Utilização

## 🎨 Geração de Imagens

Siga estas instruções para garantir o padrão visual do projeto:

1. **Prompt Global:** Antes de criar qualquer imagem, utilize obrigatoriamente o prompt global. Ele está localizado no arquivo: `Destiny_in_the_Deck_Prompts_Gemini.md`.
2. **Prompts Específicos:** Em seguida, use os prompts individuais que estão detalhados em cada arquivo para gerar a imagem correspondente.

---

## 💻 Fluxo de Trabalho e Comandos Git

Siga este passo a passo sempre que for adicionar uma nova imagem ao projeto para evitar conflitos de versão:

### 1. Atualize o Repositório
**Antes** de começar a gerar qualquer imagem, baixe as atualizações mais recentes do repositório remoto:
```bash
git pull origin main
```

### 2. Validação Visual
Após concluir a imagem e inseri-la no arquivo, utilize a extensão **Markdown Preview Enhanced** para visualizar e marcar a imagem como concluída.

### 3. Salve as Modificações
Adicione as alterações ao *stage* do Git:
```bash
git add .
```

### 4. Crie o Commit
Faça o commit seguindo o padrão de nomenclatura do projeto. Use o prefixo `feat:` seguido do nome da pasta e da imagem/evento:
```bash
git commit -m "feat: [nome da pasta]/[nome do evento]"
```
> **Exemplo Prático:** `git commit -m "feat: background/Evento 1"`

### 5. Envie para o Repositório
Por fim, envie suas atualizações para o repositório remoto:
```bash
git push origin main
```