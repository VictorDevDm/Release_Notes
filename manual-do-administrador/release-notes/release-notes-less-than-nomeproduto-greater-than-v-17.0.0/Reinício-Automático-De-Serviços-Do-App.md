# Reinício Automático de Serviços do App

**ID da US: US-NPD-8126**

Descrição: No aplicativo, se o dispositivo perder a conexão, os serviços serão reiniciados automaticamente para garantir que tudo continue funcionando sem problemas. Um comando chamado START_SERVICES será enviado ao dispositivo para restabelecer a comunicação. Se, por algum motivo, a conexão não for restabelecida em uma hora, o comando será enviado novamente. Isso assegura que o aplicativo continue operando sem interrupções, mesmo que ocorram falhas temporárias na comunicação.