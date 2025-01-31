# Forever on the Eights :sunny: :cloud_with_rain: :tv:
A nostalgic weather display app with a 90s aesthetic, featuring local weather conditions and background music from the Apple Music API.

## Description
This project creates a retro-style weather display inspired by the classic "Local on the 8s" segments from The Weather Channel. The app features:

- Local weather conditions based on the user's geolocation
- A nostalgic 90s-inspired design with CRT screen effects
- Background music playback from the Apple Music API
- A retro-style interface with green-on-black text and scanlines

## Installation
To set up this project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/https://github.com/peaster/forever-on-the-eights
   cd forever-on-the-eights
   ```
2. Install the required dependencies: 
```bash
npm install
```
 

3. Set up your API keys: 
- Create a .env.local file in the root of your project
- Add your OpenWeatherMap API key:
  ```
  WEATHER_API_KEY=your_openweathermap_api_key_here
  ```
- Add your Apple Music API credentials:
  ```
  APPLE_MUSIC_KEY=your_apple_music_key_here
  APPLE_MUSIC_SECRET=your_apple_music_secret_here
  ```   
     
     

4. Start the development server: 
```bash
npm run dev
```     
     
## Usage 
1. Open the app in your web browser at http://localhost:3000
2. Allow the app to access your location when prompted
3. Enjoy the retro-style weather display and background music!
     

## Features 

    Retro Design : Featuring a CRT screen effect with scanlines and flicker animation
    Local Weather : Displays current weather conditions, temperature, and location
    90s Music : Plays curated 90s playlists from the Apple Music API
    Geolocation Support : Automatically detects your location for local weather
    Responsive Design : Works on both desktop and mobile devices
     

## Contributing 
Contributions are welcome! If you'd like to contribute to this project, please: 

1. Fork the repository
2. Create a new feature branch:
```bash
    git checkout -b feature/your-feature-name
```
3. Commit your changes with clear commit messages
4. Push your branch to your forked repository
5. Open a Pull Request against the main branch
     

Please adhere to this project's code of conduct and styling guidelines when contributing. 
License 

This project is licensed under the MIT License. See the LICENSE  file for more details. 
## Acknowledgments 
- [OpenWeatherMap API](https://openweathermap.org/api)  for weather data
- Apple Music API  for music integration
- React Icons  for retro-style icons
- Next.js  for the application framework
     
## Roadmap 
- Add more weather details (humidity, wind speed, etc.)
- Include a retro-style radar animation
- Add more interactive elements
- Implement proper error handling
- Add a toggle for different color schemes
- Include a "Now Playing" display for the music
     
## Contact 
If you have any questions or suggestions, feel free to reach out to the maintainers at [git@peaster.io] or [@peaster](https://github.com/peaster). 