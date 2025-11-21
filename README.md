# Robo-Financeiro

Robô Financeiro via WhatsApp (Python + Twilio + Flask)
Um bot financeiro integrado ao WhatsApp que permite ao usuário registrar gastos, consultar relatórios e configurar envios automáticos.
O sistema foi desenvolvido para ser simples, direto e ideal para uso pessoal ou como serviço por assinatura.
🚀 Funcionalidades
✔ Registro de gastos
O usuário envia mensagens como:
“Gastei 25 no mercado”
O bot detecta o valor e salva automaticamente.
✔ Menu interativo
Comando: menu
Opções:
Registrar gasto
Relatório de hoje
Relatório da semana
Relatório do mês
Exportar PDF (opcional)
Configurar relatórios automáticos
Sair
✔ Relatórios automáticos
Envio diário, semanal ou mensal usando jobs agendados (APScheduler ou Celery).
✔ Banco de dados
Armazena:
gastos
usuários
configurações de relatórios
🧱 Tecnologias Utilizadas
Python 3
Flask
Twilio WhatsApp API
Mysql
APScheduler / Celery (para tarefas automáticas)
Docker (opcional)
