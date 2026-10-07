# Mapeamento Eleitoral: Diogo Segabinazzi Siqueira (PL 2244) - Deputado Federal RS 2026

Aplicação web interativa com mapas coropléticos e detalhamento de votação por município, zona eleitoral, seção e local de votação para a campanha vitoriosa de **Diogo Segabinazzi Siqueira (PL)** à Câmara dos Deputados pelo Rio Grande do Sul nas Eleições Gerais de 2026.

## 📊 Principais Números Oficiais (TSE)

- **Total de Votos Nominais:** **93.067** (Eleito)
- **Municípios com Votação:** **438 de 497** municípios gaúchos
- **Base Central (Bento Gonçalves):** **32.315 votos** (34,7% do total estadual)
- **Outros destaques regionais:**
  - Farroupilha: 6.602 votos
  - Garibaldi: 5.939 votos
  - Caxias do Sul: 4.930 votos
  - Carlos Barbosa: 4.709 votos
  - Veranópolis: 4.513 votos
  - Nova Prata: 4.236 votos
  - Guaporé: 2.421 votos
  - Porto Alegre: 2.088 votos

---

## 🚀 Funcionalidades da Página

1. **Mapa Interativo do RS com Leaflet.js**:
   - Escala de calor (coropleta) evidenciando a concentração eleitoral na Serra Gaúcha e a abrangência em todo o RS.
   - Tooltips com nome do município, total de votos recebidos e representatividade percentual.
2. **Detalhamento Completo ao Clicar na Cidade**:
   - Ao clicar em qualquer município (com destaque para Bento Gonçalves), abre-se a gaveta lateral contendo a separação por **Zona Eleitoral**, **Local de Votação (Nome e Endereço)** e **Quantidade de Votos em cada Seção**.
   - Campo de busca instantânea para filtrar por escola, bairro ou número de seção.
3. **Exportação em Imagem**:
   - Botão integrado **"Exportar Imagem"** que gera um arquivo `.png` em alta resolução do mapa e painéis visíveis no momento, pronto para relatórios e redes sociais.
4. **Totalmente Responsivo**:
   - Adaptado para visualização em computadores, tablets e smartphones (Android e iOS).

---

## 🗂️ Fonte dos Dados

Os dados foram extraídos diretamente do **Portal de Dados Abertos do Tribunal Superior Eleitoral (TSE)**:
- Arquivo: `votacao_secao_2026_RS.csv`
- Candidato: **DIOGO SEGABINAZZI SIQUEIRA** (Número de Urna: **2244** | Partido: **PL**)
- Cargo: **Deputado Federal**

---

## 🌐 Como Visualizar via GitHub Pages

Para publicar esta aplicação gratuitamente:
1. Vá até as **Configurações (Settings)** do repositório no GitHub.
2. Acesse a aba **Pages** no menu lateral.
3. Em **Build and deployment > Branch**, selecione a branch `main` e a pasta `/ (root)`.
4. Clique em **Save**. Em instantes a página estará disponível publicamente no endereço `https://hateixeira.github.io/diogo-deputado-2026/`.
