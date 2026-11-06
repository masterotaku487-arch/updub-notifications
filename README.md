# Up Dub+ Notifications

Arquivo público de notificações do aplicativo Up Dub+.

Edite `notifications.json` diretamente pelo GitHub. Cada aviso deve conter:

```json
{
  "id": "aviso-unico-2026-11-06",
  "type": "app",
  "title": "Título do aviso",
  "message": "Texto que aparecerá no aplicativo.",
  "date": "2026-11-06T22:00:00-03:00"
}
```

Tipos aceitos: `app` para avisos do aplicativo e `launch` para lançamentos.
Após salvar o arquivo na branch `main`, o app buscará a atualização automaticamente na próxima abertura ou recarga.
