# Cron Jobs
Projeto criado para estudar e praticar o uso de cron jobs no Linux.

---

## O que são Cron Jobs?
Cron jobs são tarefas agendadas que rodam automaticamente em horários definidos no Linux.

---

## O que esse projeto faz?
- Salva a data e hora atual a cada 1 minuto em `minuto.txt`
- Salva a data e hora atual a cada 2 minutos em `dois-minuto.txt`
---

## Como para a execução?
- Para **pausar** uma cron específica, abra o crontab:

```
crontab -e
```

E coloque um `#` na frente da linha que quer pausar:

```
# * * * * * ~/script1
```

O `#` transforma a linha em comentário e ela para de executar.

Para **finalizar/remover** de vez, é só apagar a linha completamente e salvar.

---
## Tecnologias usadas
- Linux
- Bash
- Crontab
