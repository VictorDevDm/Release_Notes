# Reinício Automático de Serviços do App

**ID da US: US-NPD-8126**

O app agora possui uma funcionalidade que garante que seus serviços sejam reiniciados automaticamente para manter a comunicação sempre ativa. Se o dispositivo perder a conexão com a rede, o sistema envia um comando para reiniciar esses serviços. Se a comunicação não for restabelecida dentro de 1 hora, o comando será enviado novamente, garantindo que o app continue funcionando sem interrupções.