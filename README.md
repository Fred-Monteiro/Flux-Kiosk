# Flux Kiosk

Aplicativo Android que transforma um tablet ou celular em **painel de parede**: mostra uma página web (por exemplo um dashboard do Home Assistant) em tela cheia, sem menus, e se recupera sozinho quando a página trava.

*An Android kiosk app for wall-mounted tablets, built for Home Assistant dashboards.*

## Onde baixar

Em breve na **Google Play**, a única forma oficial de obter o app.

## O que ele faz

- Página em tela cheia, com recuperação automática quando a página congela ou falha.
- Proteção de tela OLED: escurece após X minutos sem toque ou num horário noturno; um toque acorda.
- Agenda de brilho e brilho controlado pelo Home Assistant.
- Acordar pela câmera (opcional): com a tela escura, acorda quando alguém passa. As imagens não são gravadas nem enviadas.
- Integração com o Home Assistant por MQTT (o aparelho aparece sozinho) ou por controle remoto HTTP com token.
- Página de status acessível pelo navegador de outro aparelho da rede.
- PIN para o painel de configurações.

## Privacidade

O app não tem conta, não tem anúncios e não coleta dados. Ele só se conecta aos endereços que você configurar. Detalhes: [Política de privacidade](PRIVACY.md).

## Licença

Todos os direitos reservados. Veja [LICENSE.md](LICENSE.md).
