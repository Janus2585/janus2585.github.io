The google font was changed to load via ansyncronous javascript. This allows the rest of the website to load before the font loads.
The href link to css/print.css was modified to have media = "print" at the end to only load css/print.css while printing.
The <script> for "http://www.google-analytics.com/analytics.js" was modified to insert an async command.
Pizzeria.jpg was compressed and optimized to reduce the resolution of the picture.
style.css was moved to be inline with index.html to reduce the time requesting and waiting for a server response for style.css