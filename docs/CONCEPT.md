# Концепт NEURAL PORTFOLIO CONTROL

## Проблема
Фрилансеры и AI-агентства ведут задачи в одном месте, финансы — в другом, дизайн — в третьем, уведомления — отдельно.

## Решение
Один продукт, который объединяет:
1. Управление задачами и проектами (TaskControl-style)
2. Финансовый обзор (eToro watchlist + balances)
3. Дизайн-активы (Canva + Figma)
4. Автоматизацию отчётов и триггеров
5. Голосовые и email-уведомления

## Архитектура
- Frontend: Vanilla JS / React
- Backend: Supabase + RLS
- Data: eToro Public API (read-only для демо)
- Design: Canva + Figma
- Ops: GitHub + Automations + Gmail + Voice

## Уникальность
Продукт создан **в реальном времени** с использованием всех подключённых коннекторов одновременно.