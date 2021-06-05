<h1 align="center">
REACT NATIVE - Agendamento para barbeiros
</h1>
## Participants

[<img src="https://avatars.githubusercontent.com/u/20409822?v=4" width="75px;"/>](https://github.com/adisiojunior)

[Adísio Fialho Jr](https://github.com/adisiojunior)

## Feito até o momento
- [x] Tela de inicalização
- [x] Tela de login
- [x] Tela de Cadastro
## Techs

- [x] React Native
- [x] Styled Components

## bibliotecas 
Instalando algumas bibliotecas importante para o projeto
Para estilizar as págias:
    - npx install styled-components
 ou - npx instal styled

Para navegar entra páginas
    - npm install @react-navigation/native
   Instalando demais dependencias do navigation
    - npm install react-native-reanimated react-native-gesture-handler react-native-screens react-native-safe-area-context @react-native-community/masked-view
    - npm install @react-navigation/stack
    - npm install @react-navigation/bottom-tabs

Para fazer o login, usando Token:
   - npm install @react-native-community/async-storage

Para localização:
   - npm install @react-native-community/geolocation
   Precisa ter uma permissão para acessar as localizações
      - npm install react-native-permissions
      configurando no android?
         Acessa as seguintes pastas:
            - android
            - scr
            - main
            - Arquivo: AndroiManifest.xml (<uses-permission android:name="android.permission.ACCESS_FINE_LOCATION" />)

Swiper:
   - npm install react-native-swiper

SVG:
   - npm install react-native-svg
   - npm install react-native-svg-transformer
   Acessar o site: https://github.com/kristerkari/react-native-svg-transformer
   e editar o metro.config.js
