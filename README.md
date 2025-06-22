📋 LISTA COMPLETA DE COMANDOS

🎯 COMANDOS DE EVENTOS (Enquete)
• Permissão necessária: Cargo "Puxadores"

🔹 /criar_evento_boss
  • Descrição: Criar uma nova enquete para eventos de boss
  • Funcionalidade: Abre um modal para configurar evento com limite de jogadores por categoria (TANKER, HEALER, DPS, RESERVA)
  • Como usar: Execute o comando e preencha o formulário com título, horário e limites de cada categoria

🔹 /resultado_evento
  • Descrição: Ver resultados dos últimos eventos criados
  • Funcionalidade: Mostra os 5 eventos mais recentes com lista de participantes
  • Como usar: Execute o comando e selecione um evento para ver detalhes completos

🔹 /deletar_eventos
  • Descrição: Deletar eventos salvos do armazenamento
  • Funcionalidade: Lista todos os eventos e permite deletar múltiplos por vez
  • Como usar: Execute o comando, selecione os eventos para deletar e confirme

🔹 /limpar_evento
  • Descrição: Limpar enquetes da memória
  • Funcionalidade: Remove dados temporários de enquetes ativas
  • Como usar: Execute quando houver problemas com botões de enquetes

🔧 COMANDOS DE GERENCIAMENTO (Cargos)
• Permissão necessária: Permissão "Gerenciar Cargos"

🔹 /gerenciar_cargos [cargo]
  • Descrição: Adicionar ou remover cargos de múltiplos membros
  • Parâmetro opcional: cargo - Cargo específico para gerenciar
  • Funcionalidade: Interface completa para gerenciamento em massa de cargos
  • Como usar: Execute sem parâmetro para escolher cargo, ou com cargo específico

🔐 COMANDOS DE VERIFICAÇÃO (Novos Membros)
• Permissão necessária: Administrador

🔹 /criar_painel_verificacao [canal]
  • Descrição: Criar painel de verificação para novos membros
  • Parâmetro opcional: canal - Canal onde criar o painel
  • Funcionalidade: Cria sistema interativo de verificação com nickname e vocação
  • Como usar: Execute no canal desejado ou especifique um canal

🔹 /verificar_cargos
  • Descrição: Verificar se todos os cargos necessários existem
  • Funcionalidade: Verifica existência dos cargos: Convidado, EK, MS, RP, ED, MK
  • Como usar: Execute para diagnóstico do sistema de verificação

🔹 /resultado_verificacao
  • Descrição: Ver lista completa de novos membros verificados
  • Funcionalidade: Mostra estatísticas e histórico de verificações
  • Como usar: Execute para ver relatório completo de verificações

⚙️ COMANDOS ADMINISTRATIVOS
• Permissão necessária: Administrador

🔹 /sync_comandos
  • Descrição: Forçar sincronização dos comandos slash
  • Funcionalidade: Atualiza comandos no Discord quando há problemas
  • Como usar: Execute quando comandos não aparecem ou não funcionam

🎮 SISTEMAS INTERATIVOS

🔸 Sistema de Eventos
  • Criação de enquetes com botões interativos
  • Categorias: TANKER (🛡️), HEALER (🚑), DPS (⚔️), RESERVA (🔄)
  • Limite configurável por categoria
  • Lista automática de participantes
  • Salvamento persistente em JSON

🔸 Sistema de Verificação
  • Painel persistente para novos membros
  • Processo em 3 etapas:
    ◦ Definir nickname do servidor
    ◦ Receber cargo "Convidado" automaticamente
    ◦ Escolher vocação obrigatória (EK, MS, RP, ED, MK)

🔸 Sistema de Gerenciamento de Cargos
  • Interface com dropdowns para seleção múltipla
  • Visualização de membros com/sem cargo
  • Seleção em massa (todos/nenhum)
  • Confirmação antes de aplicar mudanças

📊 RECURSOS ESPECIAIS
• Logging completo: Todas as ações são registradas com horário de Brasília
• Armazenamento persistente: Dados salvos em JSON para eventos e verificações
• Interface responsiva: Botões e dropdowns com feedback visual
• Verificação de permissões: Controle de acesso por cargo/permissão
• Views persistentes: Painéis que funcionam mesmo após restart do bot
• Relatórios detalhados: Estatísticas e históricos completos

ℹ️ Todos os comandos usam slash commands ( / ) e têm verificação de permissões apropriadas para cada função.
