## **RNF01 - Intervalo de Atualização de Localização:**

### O sistema deve atualizar a posição do veículo e o tempo estimado de chegada (ETA) no mapa do aplicativo a cada 10 a 15 segundos, utilizando SDKs prontos de mapas (como Google Maps) para economizar processamento do servidor e a bateria do dispositivo.

## **RNF02 - Disparo Simplificado de Alerta de Emergência:**
### O acionamento do Botão de Pânico ou do Alerta Mecânico deve enviar uma requisição HTTP simples contendo ID e coordenadas de GPS para o servidor em até 5 segundos.

## **RNF03 - Reconhecimento de Voz Nativo:**
### A funcionalidade de voz do motorista deve utilizar as bibliotecas naticas de conversão de fala em texto (Speech-to-Text) do próprio sistema operacional (Android/iOS), eliminando a necessidade de desenvolver modelos próprios de IA.

## **RNF04 - Envio de Notificações por Serviço Gerenciado:**
### Os avisos sobre imprevistos e alterações de itinerário devem ser entregues aos usuários em até 30 segundos, utilizando plataformas gerenciadas como Firebase Cloud Messaging (FCM) ou OneSignal.

## **RNF05 - Autenticação e Permissão por Perfil:**
### O acesso às funções de alteração de rota deve ser restrito através de login com senha e controle de acesso baseado em perfis (RBAC - Role-Based Access Control), separando usuários comuns de administradores autorizados.
