# Política de privacidade do Flux Kiosk

*Última atualização: 23 de setembro de 2026.* ([English below](#privacy-policy-english))

O Flux Kiosk transforma um tablet ou celular em painel de parede, mostrando uma página web escolhida por você (por exemplo, um dashboard do Home Assistant).

## Resumo

**O Flux Kiosk não coleta, não vende e não compartilha dados pessoais.** Não tem conta, anúncios, análise de uso nem relatórios de falha enviados para o desenvolvedor.

## O que fica no aparelho

Tudo o que você configura fica **somente no próprio aparelho**, na área privada do app: o endereço da página, favoritos e histórico, horários de escurecimento e de brilho, o PIN do painel (guardado apenas como resumo criptográfico, nunca o número), o token do controle remoto, o endereço, usuário e senha do servidor MQTT e um identificador aleatório do aparelho para o Home Assistant. Esses dados não entram em backups na nuvem nem são copiados para outros aparelhos. Desinstalar o app apaga tudo.

## Com quem o app se conecta

Somente com os endereços que **você** configurar:

- a página que o app exibe, que funciona como num navegador comum e segue a política de privacidade de quem a publica;
- o seu servidor MQTT, se você ligar o MQTT;
- aparelhos da sua rede que chamem o controle remoto, se você ligá-lo (protegido por token).

## Câmera

A câmera só é usada se você ligar a opção "Acordar ao ver movimento na câmera", e só enquanto a tela está escurecida. As imagens são analisadas na memória, em baixa resolução, apenas para detectar mudança; **nunca são gravadas, exibidas ou enviadas** a ninguém.

## Crianças

O app não é direcionado a crianças e não coleta dados de ninguém.

## Mudanças e contato

Mudanças nesta política serão publicadas nesta página. Dúvidas: use o e-mail de contato do desenvolvedor informado na página do Flux Kiosk na Google Play.

---

# Privacy policy (English)

*Last updated: September 23, 2026.*

Flux Kiosk turns a tablet or phone into a wall panel that shows a web page you choose (for example, a Home Assistant dashboard).

**Flux Kiosk does not collect, sell or share personal data.** There are no accounts, ads, analytics or crash reports sent to the developer.

**Stored on the device only:** everything you configure (page address, favorites and history, dimming and brightness schedules, the settings PIN, stored only as a cryptographic hash, the remote control token, the MQTT server address, user name and password, and a random device identifier for Home Assistant). This data is excluded from cloud backups and device-to-device transfers. Uninstalling the app deletes it.

**Network connections:** only to the addresses you configure: the page the app displays, which behaves like a regular browser and follows its publisher's privacy policy; your MQTT server, if enabled; and devices on your network calling the token-protected remote control, if enabled.

**Camera:** used only if you turn on "wake on camera motion", and only while the screen is dimmed. Low-resolution frames are analyzed in memory to detect change; they are **never stored, displayed or sent** anywhere.

**Children:** the app is not directed at children and collects no data from anyone.

**Changes and contact:** changes will be posted on this page. Questions: use the developer contact e-mail shown on the Flux Kiosk page on Google Play.
