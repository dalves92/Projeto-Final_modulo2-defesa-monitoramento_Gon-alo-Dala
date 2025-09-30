# Projeto-Final_modulo2-defesa-monitoramento-Goncalo_Dala
RELATÓRIO – Opção 1 (Hands‑on)
Projeto Final – Lab de Segurança (WAF + DVWA)
📘 Visão Geral

Este projeto demonstra a proteção de uma aplicação vulnerável (DVWA) utilizando um WAF (NGINX + ModSecurity + OWASP CRS) contra ataques simulados:

Reconhecimento com nmap

SQL Injection (SQLi)

Cross-Site Scripting (XSS)

⚙️ Metodologia

Reconhecimento → nmap identificando portas/serviços

Ataques Controlados → SQLi e XSS via curl/browser

WAF – Detection Only → requisições logadas (HTTP 302)

WAF – Blocking Mode → ataques bloqueados (HTTP 403)

Resposta NIST IR → Detecção, Análise, Contenção, Erradicação, Recuperação

🛡️ Resultados

SQLi e XSS detectados e bloqueados com eficácia

Logs detalhados confirmaram eventos e regras acionadas

Aplicação permaneceu disponível para tráfego legítimo

✅ Recomendações

Ativar WAF permanentemente em modo blocking

Integrar logs em um SIEM

Atualizar CRS/ModSecurity regularmente

Criar playbooks de resposta rápida



✍️ Autor: Gonçalo Quissola Dala
