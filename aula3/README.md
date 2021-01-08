# Aula 3: front end mobile - Materiais de apoio

## Telas do sistema

https://www.figma.com/file/LAIvIzyaJsSl2A9NMrnR7W/DSDeliver01

https://www.figma.com/file/sagWrEqbSarTcpE6Sybgtk/DSDeliver02

https://www.figma.com/file/BVpIFfl1pHNaQo3T2hwONn/DSDeliver03

https://www.figma.com/file/pHfpDnEZYtWOQ9WGDVuCsu/DSDeliver04

https://www.figma.com/file/BMIYHhdtpAXQgAPPDWLi18/DSDeliver05

## Passo a passo de configuração do projeto:

#### Instando o `Expo` globalmente:
```bash
npm install --global expo-cli
```
#### Criando projeto com `Expo`:
```bash
expo init front-mobile -t expo-template-blank-typescript --npm
```
#### Após a instalação,  remover a pasta `.git` de DENTRO DA PASTA `front-mobile`  (MUITA ATENÇÃO NESSE PASSO!)
```bash
rm -rf .git
```
#### Instalando dependências:
```bash
expo install @react-navigation/stack @react-native-community/masked-view react-native-screens react-native-gesture-handler @react-navigation/native expo-app-loading @expo-google-fonts/open-sans expo-font
```
#### Acesso URL do Google Maps:
`https://www.google.com/maps/dir/?api=1&travelmode=driving&dir_action=navigate&destination=${order.latitude},${order.longitude}`

## Links úteis:
- https://docs.expo.io/
- https://docs.expo.io/guides/using-custom-fonts/
- https://reactnative.dev/docs/images
- https://docs.expo.io/get-started/installation/#2-expo-client-app-for-ios-and
