# Simulador simples de Google Ads (RSA) — Treinamento

Um simulador leve (1 arquivo) feito em **HTML + CSS + JavaScript** para treinar criação de **Responsive Search Ads (RSA)**.  
A tela é dividida em **duas sessões**:

- **Sessão 1 (esquerda):** onde o “gestor de anúncios” preenche ativos (títulos, descrições, palavras-chave, URL etc.)
- **Sessão 2 (direita):** **preview** do anúncio no estilo SERP (resultados do Google)

> Objetivo: treinamento prático de copy e estrutura de anúncios (não é um espelho perfeito do Google Ads).

---

## ✅ O que este simulador faz

### 1) Combinação estilo RSA (Responsive Search Ad)
- Você cadastra **vários títulos** e **várias descrições**
- Ao clicar em **“rodar campanha”**, o simulador escolhe automaticamente:
  - **3 títulos** (aleatórios)
  - **2 descrições** (aleatórias)
- Gera uma variação diferente a cada clique (ótimo para treinamento de consistência).

### 2) Contadores e alertas de limites
- Títulos: **até 30 caracteres**
- Descrições: **até 90 caracteres**
- Paths (URL exibida): **até 15 caracteres**
- Mostra “ok/estourou” para ajudar na disciplina de criação.

### 3) Destaque de palavras-chave (didático)
- Se ativado, o simulador destaca as palavras-chave na descrição do preview.
- Serve para treinar aderência da mensagem ao termo de busca (sem prometer relevância real).

### 4) Sitelinks (opcional)
- Permite inserir sitelinks para enriquecer o preview (treino visual).

---

## 📦 Como usar

### Opção A — 100% local (recomendado)
1. Crie um arquivo chamado `index.html`
2. Cole dentro dele o código completo do simulador
3. Abra o arquivo no navegador (Chrome/Edge/Firefox)

Pronto. Não precisa instalar nada.

---

## 🧠 Como preencher (treinamento rápido)

### Títulos (Headlines)
- Um título por linha
- Ideal para treinar: **8 a 15 títulos**
- Dicas:
  - Varie ângulos: benefício, prova, objeção, urgência, diferencial
  - Evite repetir a mesma frase com pequenas mudanças

### Descrições (Descriptions)
- Uma descrição por linha
- Ideal para treinar: **3 a 6 descrições**
- Dicas:
  - Estrutura recomendada:
    - Dor → Solução → Prova → CTA
  - Seja específico (quando verdadeiro)

### Palavras-chave (Keywords)
- Uma keyword por linha
- Use para treinar:
  - consistência de mensagem
  - termos centrais do produto/serviço

### Sitelinks (opcional)
Formato:  
`Texto | URL`

Exemplo:
`Preços | https://seusite.com.br/precos`

---

## 🎛️ Controles

- **rodar campanha:** gera uma variação (3 títulos + 2 descrições) no preview
- **preencher exemplo:** popula os campos com um cenário pronto para teste
- **destacar palavras-chave:** marca keywords no preview (didático)
- **preview ao digitar (live):** atualiza automaticamente enquanto você edita

---

## 🧩 Estrutura dos campos

- **Nome da marca:** texto livre (apenas para o preview)
- **URL final:** referência (não executa tracking nem validações reais)
- **Domínio exibido + Path 1/2:** compõe a URL mostrada no preview

---

## Limitações (importante para alinhamento)
- O Google Ads pode variar:
  - ordem e quantidade de títulos exibidos
  - quebras de linha
  - extensões
  - presença/ausência de elementos
- Este projeto **não simula leilão**, qualidade, política editorial, nem CTR real.
- O destaque de keywords é apenas para treinamento visual.

---

## ✅ Boas práticas de treinamento (roteiro sugerido)

1. Peça ao aluno criar:
   - 10 títulos
   - 4 descrições
   - 10 keywords
2. Clique em **rodar campanha** 10 vezes e avalie:
   - coerência das combinações
   - promessa x prova
   - clareza do CTA
   - repetição e redundância
3. Ajuste os ativos e repita.

---

## Personalização rápida

Você pode editar no próprio HTML:
- textos padrão do preview
- cores e layout no CSS (sessão `<style>`)
- regras de seleção aleatória no JS

Sugestões de upgrade (mantendo simples):
- incluir “fixar título” (pin) para simular pinning do RSA
- incluir score de qualidade (repetição, CTA, vaguidão)
- exportar/importar campanha em JSON

---

## Licença / uso
Uso livre para treinamento interno e prototipação.
