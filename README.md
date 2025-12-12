Файлы оживления Discord для импортирования в конфиг MiHomo 

  discord-domains:
    type: http
    behavior: classical
    format: yaml
    url: https://github.com/G1rOMan/Mihomo/blob/main/discord.yaml
    path: ./rule-sets/discord.yaml
    interval: 86400
  discord-ip:
    type: http
    behavior: classical
    format: yaml
    url: https://github.com/G1rOMan/Mihomo/blob/main/discord-ip.yaml
    path: ./rule-sets/discord-ip.yaml
    interval: 86400
