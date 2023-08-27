## Mobile Map Controls / .NET MAUI

https://learn.microsoft.com/en-us/dotnet/maui/user-interface/controls/map
https://learn.microsoft.com/en-us/dotnet/maui/platform-integration/device/geolocation?tabs=android
<br>
### MAUI Lat Lon Grab

General
```
var location = await Geolocation.GetLocationAsync();

double latitude = location.Latitude; // Property 1

double longitude = location.Longitude; // Property 2
```
 <br>

(iOS Better Solution)
```
Location location = await Geolocation.Default.GetLastKnownLocationAsync();
```

### Accuracy

Lowest
```
Android - 500m

iOS/macOS - 3000m

Windows - 1000-5000m
```
Highest
```
Android - 0-100m

iOS/macOS - 0m

Windows - 0-10m
```
testing