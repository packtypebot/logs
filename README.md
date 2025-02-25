# 📝 Log de Versões

## 🚀 Versão 5 - 25/02/2025

FIX: Envio de midia na fila (QueueOptionController.ts, QueueController.ts, wbotMessageListener.ts)
FIX: ,Contact (Erro de digitação) "Linha 2108: const body = `\u200e ${whatsapp.outOfHoursMessage}`;" (wbotMessageListener.ts)

Correção do envio de fila WHATICKET:

Removemos a verificação baseada em regex que impedia a seleção de filas após uma mensagem inválida. Agora, qualquer entrada numérica válida é aceita, independente da última mensagem enviada pelo bot.

Ao enviar a mensagem de opção inválida, incluímos novamente a lista de opções para que o usuário possa tentar novamente.

Arquivo: backend/src/services/WbotServices/wbotMessageListener.ts

✅ Correção ao Redimensionar Área de Ticket: Erro corrigido ao redimensionar.  
✅ Correção de toastError.js: Problema resolvido no `toastError.js`.  
✅ Validação do Número no ContactModal: Validação aprimorada.  
✅ Atualização OpenAI: Atualização para versão "openai": "3.3.0" e wbotMessageListener.ts.  
✅ Correção nas Avaliações de 1 para 5: Ajuste nas avaliações de 1 a 5 estrelas.  
✅ Mensagem de Avaliação Somente Quando o Ticket Estiver em Atendimento: Avaliações só aparecem quando o ticket está ativo.  
✅ Horários Intercalados: Implementação de horários intercalados.  
✅ Alteração de LOGO de Acordo com LIGHT e DARK: Logo ajustado conforme o tema.  
✅ Inserido no Kanban e Reformulado
✅ Fix Audio no iPhone (Não estava reproduzindo)
✅ Correção Chat no modo Dark
✅ Inserido pastas por empresas na "public"
