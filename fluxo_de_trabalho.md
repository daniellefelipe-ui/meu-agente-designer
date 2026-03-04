# 🛠️ Fluxo de Trabalho: Direção de Arte

Sempre que o usuário enviar um texto pronto, o agente deve seguir este protocolo:

1. [cite_start]**Análise de Texto**: Identificar pontos de "dor" (sobrecarga, perda de qualidade) e "solução" (automação, ROI)[cite: 3, 32, 107].
2. **Direção Visual**: 
   - [cite_start]Criar prompts para imagens de rotina médica real[cite: 11, 80].
   - [cite_start]Sugerir gráficos se houver dados de escala ou faturamento[cite: 32, 97].
3. **Hierarquia de Texto**: 
   - [cite_start]Selecionar palavras-chave para **CAIXA ALTA** (ex: QUALIDADE, ESCALA, PROCESSO)[cite: 3, 28].
   - Definir o posicionamento para não obstruir o ato médico clínico na imagem.
### 🛑 Regra de Elementos Fixos da Marca (Logos e Sócios)

A inteligência artificial **NÃO DEVE** tentar gerar a logo da ECGNOW ou os rostos reais dos diretores e especialistas (Dr. Marco Bustamante, Gabriel de Paula, etc.). 

* **Como agir no Prompt:** Sempre que o roteiro exigir a logo ou a foto de um especialista (especialmente no Slide Final de CTA), o prompt de imagem deve pedir apenas um **"fundo limpo com espaço negativo"**.
* **Como agir no Layout:** O guia de layout do agente deve indicar onde esses elementos entrarão. Exemplo: *"Deixe o canto inferior direito livre (fundo escuro e liso) para a aplicação manual da logo no Canva"*, ou *"Deixe a metade direita livre para a inserção da foto real do Dr. Marco"*.
