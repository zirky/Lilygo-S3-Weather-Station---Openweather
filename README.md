# Lilygo-S3-Weather-Station---Openweather
A compact weather station using ESP32 to fetch and display current weather and 3-day forecasts on a TFT screen. Features include automatic brightness adjustment, screen rotation, and WiFi connectivity. Built with Arduino, it uses OpenWeatherMap API for data and libraries like TFT_eSPI, WiFiManager, and NTPClient. Perfect for DIY weather monitoring!


---

## English Description

### Weather Station with TFT Display and ESP32

This project is a weather station that displays current weather conditions and a 3-day forecast on a TFT display. It uses an ESP32 microcontroller to fetch weather data from the OpenWeatherMap API and displays it in a user-friendly format. The project also includes features like automatic brightness adjustment based on the time of day and screen rotation.

#### Features:
- **Current Weather**: Displays the current temperature and weather description.
- **3-Day Forecast**: Shows the daytime and nighttime temperatures for the next 3 days.
- **Automatic Brightness**: Adjusts the display brightness based on the time of day (day/night mode).
- **Screen Rotation**: Allows the user to rotate the display using a button.
- **WiFi Manager**: Simplifies WiFi configuration using the WiFiManager library.
- **NTP Time Sync**: Synchronizes the device's clock with an NTP server for accurate time display.

#### Hardware Requirements:
- ESP32 microcontroller
- TFT display (compatible with TFT_eSPI library)
- Button for screen rotation
- WiFi connection

#### Libraries Used:
- `WiFiManager` for WiFi configuration
- `TFT_eSPI` for TFT display control
- `ArduinoJson` for parsing JSON data from the API
- `NTPClient` for time synchronization
- `Timezone` for handling time zones

#### Setup:
1. Clone the repository.
2. Install the required libraries.
3. Update the `apiKey` in the code with your OpenWeatherMap API key.
4. Upload the code to your ESP32.
5. Connect the TFT display and button as per the wiring diagram.

#### Usage:
- The device will automatically connect to WiFi and fetch weather data.
- Press the button to rotate the screen.
- The display brightness will adjust automatically based on the time of day.

---

Requires registration on OpenWeatherMap for an API key (free tier available). Uses OpenWeatherMap API 3.0.

---

## Český Popis

### Meteorologická stanice s TFT displejem a ESP32

Tento projekt představuje meteorologickou stanici, která zobrazuje aktuální počasí a předpověď na 3 dny na TFT displeji. Používá mikrokontrolér ESP32 pro získání dat z API OpenWeatherMap a zobrazuje je v přehledném formátu. Projekt také obsahuje funkce jako automatické nastavení jasu podle denní doby a otáčení obrazovky.

#### Funkce:
- **Aktuální počasí**: Zobrazuje aktuální teplotu a popis počasí.
- **Předpověď na 3 dny**: Zobrazuje denní a noční teploty na následující 3 dny.
- **Automatický jas**: Nastavuje jas displeje podle denní doby (denní/noční režim).
- **Otáčení obrazovky**: Umožňuje uživateli otáčet displej pomocí tlačítka.
- **WiFi Manager**: Zjednodušuje konfiguraci WiFi pomocí knihovny WiFiManager.
- **Synchronizace času NTP**: Synchronizuje čas zařízení s NTP serverem pro přesné zobrazení času.

#### Požadavky na hardware:
- Mikrokontrolér ESP32
- TFT displej (kompatibilní s knihovnou TFT_eSPI)
- Tlačítko pro otáčení obrazovky
- Připojení k WiFi

#### Použité knihovny:
- `WiFiManager` pro konfiguraci WiFi
- `TFT_eSPI` pro ovládání TFT displeje
- `ArduinoJson` pro parsování JSON dat z API
- `NTPClient` pro synchronizaci času
- `Timezone` pro správu časových pásem

#### Nastavení:
1. Naklonujte repozitář.
2. Nainstalujte potřebné knihovny.
3. Aktualizujte `apiKey` v kódu pomocí vašeho API klíče od OpenWeatherMap.
4. Nahrajte kód do vašeho ESP32.
5. Připojte TFT displej a tlačítko podle schématu zapojení.

#### Použití:
- Zařízení se automaticky připojí k WiFi a stáhne data o počasí.
- Stisknutím tlačítka otáčejte obrazovku.
- Jas displeje se automaticky upraví podle denní doby.

---

Vyžaduje registraci na OpenWeatherMap pro klíč API (k dispozici zdarma úroveň). Používá OpenWeatherMap API 3.0.

---

### Odkazy
- [OpenWeatherMap API](https://openweathermap.org/api)
- [TFT_eSPI Library](https://github.com/Bodmer/TFT_eSPI)
- [WiFiManager Library](https://github.com/tzapu/WiFiManager)

---

![PXL_20250308_173348811 MP](https://github.com/user-attachments/assets/20c43a0d-edaa-4608-b4f6-3dbdd5331dfa)

