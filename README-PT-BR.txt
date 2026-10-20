MOVESTORE — PROJETO ANDROID
===========================

Este projeto transforma o arquivo HTML da Move Store em um app Android simples,
usando uma WebView. O conteúdo do site fica dentro do aplicativo; imagens de
produtos hospedadas em sites externos precisam de internet.

IMPORTANTE
----------
- Este ZIP contém o PROJETO-FONTE para abrir no Android Studio. Ele ainda não é
  um aplicativo compilado/instalável.
- O projeto não integra pagamentos reais nem um servidor de pedidos. O HTML
  original tem um checkout demonstrativo.
- O suporte por WhatsApp no HTML original está sem número configurado
  (SUPORTE_WHATSAPP=""). Configure o número no Index.html se quiser ativar.
- Não compartilhe dados reais de clientes antes de configurar backend, segurança
  e tratamento adequado dos pedidos.

COMO GERAR O APP NO ANDROID STUDIO
----------------------------------
1. No computador, instale o Android Studio oficial:
   https://developer.android.com/studio
2. Extraia o ZIP MoveStoreAndroid.zip.
3. No Android Studio, escolha "Open" e selecione a pasta MoveStoreAndroid
   (a pasta que contém settings.gradle).
4. Aguarde a sincronização do Gradle. Se solicitar, instale Android SDK 35.
5. Para testar: conecte um celular com depuração USB habilitada ou use um
   emulador e pressione Run (triângulo verde).
6. Para criar o arquivo instalável: Build > Build Bundle(s) / APK(s) > Build APK(s).
7. O Android Studio mostrará o caminho do APK gerado ao terminar.

REQUISITOS
----------
- Android Studio recente.
- JDK 17 (normalmente vem com Android Studio).
- Internet para baixar as ferramentas de build e carregar imagens externas.

NOME DO APP
-----------
Move Store

PACOTE
------
com.movestore.app
