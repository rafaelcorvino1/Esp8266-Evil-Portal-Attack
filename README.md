# Esp8266-Evil-Portal-Attack
![image](https://github.com/user-attachments/assets/feaee438-9067-4f02-b85a-ad4a16deda0f)
![image](https://github.com/user-attachments/assets/2043fc52-4bc7-43fd-a395-02af39bfe602)
# Configuração do Arduino IDE para ESP8266 Deauther

## 1: Configuração do Arduino IDE

1. No **Arduino IDE**,  **Arquivo -> Preferências**.
2. Adicione  URL na seção **"URLs Adicionais para o Gerenciador de Placas"**:
   ```
   https://raw.githubusercontent.com/SpacehuhnTech/arduino/main/package_spacehuhn_index.json
   ```

## 2: Instalação do Pacote Deauther

1. No **Arduino IDE**, **Ferramentas -> Placa -> Gerenciador de Placas**.
2. Pesquisar pacote **"deauther"** e instalar.

## 3: Clonando o Repositório

```bash
git clone https://github.com/SpacehuhnTech/esp8266_deauther
cd esp8266
git checkout v3
```

## 4: Abrindo o Código no Arduino IDE

Arduino IDE, abrir **"esp8266_deauther.ino"**.

## 5: Configuração da Placa

1. No **Arduino IDE**, **Ferramentas -> Placa** e selecionar **ESP8266 Deauther**.
2. Conectar **ESP8266** ao computador.
3. Selecione a porta serial em **Ferramentas -> Porta**.

## 6: Upload do Código

1. Clicar **"Enviar" (Upload)** no Arduino IDE para carregar o código no seu dispositivo.

## 7: Uso com huhnitor

Após carregar o código, utilize o terminal do **huhnitor** para interagir com o dispositivo.
