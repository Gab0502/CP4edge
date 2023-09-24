CP4 edge computing
IoT Tago+Wifi

Visão Geral
Este código Arduino foi desenvolvido para um projeto IoT que coleta dados de temperatura, umidade e luz e os envia para a plataforma TagoIO usando uma conexão Wi-Fi. Ele utiliza um sensor DHT para medir temperatura e umidade e um sensor LDR para medir a intensidade da luz.

Pré-requisitos
Antes de usar este código, certifique-se de ter o seguinte:

O IDE Arduino instalado em seu computador.
Uma placa Arduino compatível com o IDE Arduino.
A biblioteca DHT instalada em seu IDE Arduino.
A biblioteca WiFi instalada em seu IDE Arduino.
A biblioteca HTTPClient instalada em seu IDE Arduino.
Acesso a uma conta TagoIO com um token de dispositivo válido.
Um sensor DHT conectado à porta A1.
Um sensor LDR conectado à porta A0.
Credenciais de rede Wi-Fi (SSID e senha).
Configuração

Antes de carregar o código em sua placa Arduino, você precisa configurar as seguintes variáveis:

wifiSsid: Configure-o com o nome de sua rede Wi-Fi (SSID).
wifiPass: Configure-o com a senha de sua rede Wi-Fi.
serverAddress: Configure-o com o endpoint da API TagoIO para enviar dados.
tokenHeader: Configure-o com o token de dispositivo TagoIO.
Uso
Carregue o código em sua placa Arduino usando o IDE Arduino.
Abra o monitor serial para visualizar a saída.
O código se conectará à rede Wi-Fi especificada e exibirá o endereço IP local.
Em seguida, ele lerá continuamente os dados de temperatura, umidade e luz dos sensores e os enviará para o TagoIO em intervalos regulares.
Os dados são enviados em formato JSON para o TagoIO com nomes de variáveis e unidades apropriados.
Solução de Problemas

Se você encontrar algum problema com o código, considere o seguinte:

Verifique suas credenciais de rede Wi-Fi (SSID e senha).
Certifique-se de que os sensores DHT e LDR estão conectados corretamente.
Verifique se você tem as bibliotecas necessárias instaladas em seu IDE Arduino.


Integrantes
Caíque Walter Silva - RM 550693
Enrico Enricco Rossi - RM 551717
Gabriel Marquez Trevisan - RM 99227
Guilherme Nobre Bernardo - RM 908604
Silvia Kavabata - RM 97650
