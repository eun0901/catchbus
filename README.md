
# catchbus initial navigation
</br> with stack navigation
</br>
![image](https://user-images.githubusercontent.com/52804557/189521534-58ca8c86-e4da-4f71-9d05-77e4593dd992.png)

# catchbus_navigation
</br> 은정이 url :
노선 : 
const url = 'http://apis.data.go.kr/6410000/busrouteservice/getBusRouteInfoItem';
      var queryParams = `${url}?serviceKey=${API_KEY}&routeId=${routeId}`;
      xhr.open('GET', queryParams); 
      
버스 도착 : 
const url = 'http://apis.data.go.kr/6410000/busarrivalservice/getBusArrivalList'; /*URL*/
      var queryParams = `${url}?serviceKey=${API_KEY}&stationId=${ID}`;
      xhr.open('GET', queryParams);
정류소 : 
const url = 'http://apis.data.go.kr/6410000/busstationservice/getBusStationList'; /*URL*/
      var queryParams = `${url}?serviceKey=${API_KEY}&keyword=${station}`;
      xhr.open('GET', queryParams);


npm install react-native-gesture-handler

npm install react-native-vector-icons
npm install react-native-select-dropdown

npm install react-native-timeline-flatlist
구글 아이콘
https://fonts.google.com/icons?selected=Material+Icons