# Imagem Do Docker: Nginx Com Alpine e Certificado SSL autoassinado com OpenSSL

Imagem util para testar APIs em AVD (Android Virtual Devices) do Android Studio.

Pois as vezes o AVD apresenta problemas no ambiente de testes por não conseguir comunicar com HTTP, assim essa imagem recebe uma requisicao HTTPS e com o proxy reverso redireciona para a API que é HTTP.

No caso deste exemplo a API está rodando na porta 8085 da maquina local. E o AVD foi configurado para enviar requisicoes no `https://10.0.2.2:4403/`
