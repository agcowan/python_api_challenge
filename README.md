# python_api_challenge
The API project was the first project where I felt able to complete the project with minimal guidance or assistance. I dare not say competence, but I defintely felt like I understand the mechanics of the exercise.
<br>
The images show that the trends are minimal as we are one month away from equinoxes and an interesting prospect would be to rerun these same notebooks in June closer to the equinox to see the summer in the northern latitudes and in December for summer in the southern latitudes.

<br>

# Data analysis
The first hotel found for each city located in the ideal vacation destinations as calculated by running weather data searches across a complation of 637 random cities across the world.
<br>
The API calls for the OpenWeather were determined by randomly generated latitudes and longitudes, picking cities across the world. From there, I constructed linear regression models by latitude against temperature, humidity, cloud cover, and wind speed, all extremely important factors when searching for a vacation destination.
<br>
The VacationPy notebook limits the number of cities according to factors of max temperatures, humidity, and cloudiness. From there, I called the Google Near By search API for a hotel within those 14 cities which met all of the limiting factors. 