Olá,

Obrigado por se inscrever na oficina "Guia da Streamer Soberana", eu sou o piloto que conduzirá
esta atividade esta semana com vocês.

Além de agradecer o interesse, quero dar uma oportunidade para que você, caso queira, possa se 
adiantar com a instalação de alguns requisitos.

Software:

Utilizaremos nesta atividade alguns sistemas de código aberto, um deles a ser instalado no laptop
do participante, o OBS Studio, e outros dois a serem instalados em servidores Linux (sugiro Ubuntu
ou Debian), o Owncast e o Nginx com módulo de RTMP.

- OBS Studio (Apache 2.0)
  - https://obsproject.com/
- Owncast (MIT)
  - https://owncast.online/
- Nginx com mod-rtmp (2-clause BSD)
  - pacote `libnginx-mod-rtmp` no Ubuntu
  - https://github.com/arut/nginx-rtmp-module

Resumindo:

Se quiser se adiantar, providencie:

1. dois servidores Ubuntu ou Debian acessíveis via SSH
  - da para fazer com um só também, eu vou fazer com dois por fins didáticos
  - o tamanho de disco, memoria e numero de cpus não faz muita diferença neste exercício
2. OBS Studio instalado na sua máquina pessoal
3. (opcional) contas em serviços de streaming de terceiros, como Twitch, Youtube Live ou Trovo
  - a segunda parte da oficina é um relay, que retransmitirá para um ou mais servidores RTMP


Até 
