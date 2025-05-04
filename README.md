##  Weather API Request and Reflection

###  Request Setup
**Endpoint**: `https://www.weatherbit.io/api/weather-current`  
**Method**: `GET`  
**Query Parameters**:
- `q`: `City`
- `appid`: `yourAPIkey` (hidden in screenshot)
- `units`: `metric`

###  Screenshots
**Request Setup and Response in Postman**  
![Weather API Request and Reponse Setup](https://github.com/user-attachments/assets/876ba811-81fd-46b7-b620-86e384cf2d2f)
)

### 📝 Response Summary
- **City**: San Antonio 
- **Country**: US  
- **Temperature**: 21°C
- **Feels Like**: 20.4°C
- **Weather Condition**: Scattered clouds
- **Humidity**: 51%
- **Status Code**: `200 OK` (success)





### 💭 Reflection on Query Parameters
Query parameters are key to retrieving specific information from an API. In this case, using `q` for the city and `appid` for the API key was necessary to receive accurate weather data. Omitting or misspelling a parameter can result in errors like `400 Bad Request` or `401 Unauthorized`, so precision matters in API communication.
