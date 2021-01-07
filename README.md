# COVID-19_Tracker
Covid-19 cases finder using ReactJS and "https://disease.sh/" API's information

Detailed Information : 

<-- Architecture & methods -->

1. Used ReactJS functional components and hooks
2. Used Material-UI for the simple, easy and attractive UI
3. For the World Map component I have used "react-leaflet" library and it's features
4. For the Graph, I have used "react-chartjs-2" library and it's features
5. Finally "numeral" library to format and manipulate numerical outputs

<-- Design, app features and how it works ?  -->

1. First I have created a sample graphical wireframe using Draw.io
2. The app itself containes 2 sides "app__left" & "app__right" and it manages how to show in the page in different size screens
3. Included a world map and circles pointing towards the countries and respective number of cases
4. Dropdown list enables to select any country and check current records of Cases, Recovered and Deaths. 
5. Graph is included and it serves 120 days back new cases worldwide
6. Finally the "Live Cases by Country" component shows the sorted list of highest to lowest by cases with the countries.

This COVID-19 Tracker app is launched via Netlify : https://covid-19-casetracker.netlify.app
