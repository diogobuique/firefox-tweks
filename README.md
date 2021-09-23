# firefox-tweaks
Tweaks for Firefox-Developer-Edition


Digite about:config no navegador

1. procure por browser.tabs.insertRelatedAfterCurrente e ajuste para false;
2. procure por layers.acceleration.force-enabled e ajuste para true;
3. procure por gfx.webrender.all e ajuste para true;
4. procure por media.ffmpeg.vaapi.enabled e ajuste para true;
5. procure por extensions.pocket.enable e ajuste para false;
6. procure por browser.cache.disk.enable e ajuste para false;
7. procure por browser.cache.memory.capacity e defina o valor para 150000 = 150MB ou então defina para -1 para ajuste automático;
8. feche o firefox, reabra e digite about:cache para verificar as alterações.

Na sessão Desempenho:

1. usar as aceleração por hardware quando disponível (marcar como true);
2. limite de processos de conteúdo = 2.
