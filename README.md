# com.cencosud.pickingappregional
### Uso del react-native-config
##### Crear archivo .env en la raiz (crear a partir del .env.example)
##### Ej:
###### API_URL=https://myapi.com
###### GOOGLE_MAPS_API_KEY=abcdefgh

##### De esa forma se pueden acceder las variables desde la app:
import Config from "react-native-config";
console.log('API_URL: ', Config.API_URL);



