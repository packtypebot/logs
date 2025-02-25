#### 📝 Registro de Versões

### 🌟 Versão 5 - 25/02/2025

### 🔧 Correções de Bugs

- 🔄 **Melhorias no Sistema de Filas**
  - Corrigido o envio de mídia na fila (QueueOptionController.ts, QueueController.ts, wbotMessageListener.ts)
  - Corrigido erro de digitação em Contact no arquivo wbotMessageListener.ts
    ```
    Linha 2108: const body = `\u200e ${whatsapp.outOfHoursMessage}`;
    ```

### 🎯 Aprimoramento do Sistema de Filas WHATICKET

- 🔄 Removida a verificação baseada em regex que bloqueava a seleção da fila após mensagens inválidas
- ✨ Agora aceita qualquer entrada numérica válida, independentemente das mensagens anteriores do bot
- 📝 Mensagens de opção inválida agora incluem a lista de opções para nova tentativa
- 📂 Arquivo atualizado: `backend/src/services/WbotServices/wbotMessageListener.ts`

### ✅ Principais Melhorias

- 🖥️ Corrigido problema de redimensionamento da área de tickets
- 🔔 Resolvido problemas no toastError.js
- 📱 Aprimorada a validação de números no ContactModal
- 🤖 Atualizado OpenAI para versão "3.3.0"
- ⭐ Sistema de avaliação corrigido para 1 a 5 estrelas
- 📊 Implementadas mensagens de avaliação apenas para tickets ativos
- ⏰ Adicionado suporte para horários alternados
- 🎨 Troca dinâmica de logo baseada no tema Claro/Escuro
- 📋 Implementação e redesign do Kanban
- 🔊 Corrigido problemas de reprodução de áudio no iPhone
- 🌙 Correções no chat em modo escuro
- 📁 Implementadas pastas específicas por empresa em "public"


### Feito com ❤️ para uma melhor experiência do usuário
