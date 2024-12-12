# Web-Progressive-Apps
Web Progressive Apps (PWAs) are web applications that use modern web technologies to provide a native app-like experience to users. They are designed to work seamlessly on any device, delivering a fast, reliable, and engaging experience regardless of the user’s platform or browser.
HOW DOES IT WORKS?
i)It basically converts a website into a web app which can be downloaded into your device , it will fetch it resources from your website only but i will even when not connected with internet as it creates a cache in your device to store and fetch data.
ii)For this we create a mnifest.json file ith apps detail name, logo, theme, description, URL etc.
iii)Then we create a serviceworker.js file which will help in caching  resources into your device.
iv)And final in external or internal Javascript code create function to command servciceworkerjs.