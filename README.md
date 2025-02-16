# Esp8266-Evil-Portal-Attack
![image](https://github.com/user-attachments/assets/feaee438-9067-4f02-b85a-ad4a16deda0f)
![image](https://github.com/user-attachments/assets/2043fc52-4bc7-43fd-a395-02af39bfe602)
# Configuração do Arduino IDE para ESP8266 Deauther

## Passo 1: Configuração do Arduino IDE

1. No **Arduino IDE**, vá para **Arquivo -> Preferências**.
2. Adicione a seguinte URL na seção **"URLs Adicionais para o Gerenciador de Placas"**:
   ```
   https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
   ```

## Passo 2: Instalação do Pacote Deauther

1. No **Arduino IDE**, vá para **Ferramentas -> Placa -> Gerenciador de Placas**.
2. Pesquise pelo pacote **"deauther"** e instale-o.

## Passo 3: Clonando o Repositório

Execute os seguintes comandos no terminal:

```bash
git clone https://github.com/SpacehuhnTech/esp8266_deauther
cd esp8266
git checkout v3
```

## Passo 4: Abrindo o Código no Arduino IDE

1. No Arduino IDE, abra o arquivo **"esp8266_deauther.ino"** dentro da pasta **"esp8266_deauther"**.

## Passo 5: Configuração da Placa

1. No **Arduino IDE**, vá para **Ferramentas -> Placa** e selecione **ESP8266 Deauther**.
2. Conecte seu dispositivo **ESP8266** ao computador.
3. Selecione a porta serial em **Ferramentas -> Porta**.

## Passo 6: Upload do Código

1. Clique no botão **"Enviar" (Upload)** no Arduino IDE para carregar o código no seu dispositivo.

## Passo 7: Uso com huhnitor

Após carregar o código, utilize o terminal do **huhnitor** para interagir com o dispositivo.
