# API-INTEGRATION

*COMPANY NAME*: CODTECH IT SOLUTIONS

*NAME*: RIYA JAIN

*INTERN ID*:CT04DR275

*DOMAIN*: FULL STACK WEB DEVELOPMENT

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

The given task focuses on developing a responsive and interactive webpage that can fetch, process, and display data dynamically from a public API such as a weather or news service. This project aims to demonstrate the integration of front-end web technologies—namely HTML, CSS, and JavaScript—with publicly available APIs to build an application that provides real-time information to users. The primary goal is to bridge the gap between static webpage design and dynamic data-driven web development by allowing users to retrieve live information from an external data source and display it meaningfully in the browser.

In the modern web ecosystem, APIs (Application Programming Interfaces) play a crucial role in connecting web applications with real-time data sources. Instead of manually updating information, APIs allow developers to fetch live data such as weather updates, news headlines, cryptocurrency prices, or social media feeds. By integrating a public API, the webpage becomes more functional, interactive, and user-centric. This project specifically uses the Open-Meteo API, a free and reliable weather service that provides data such as temperature, wind speed, and weather conditions for a given location. Through this API, the webpage can retrieve up-to-date weather data based on the city entered by the user.

The structure of the webpage is divided into three main sections: the HTML layout, CSS styling, and JavaScript functionality. The HTML part defines the basic structure and layout of the webpage, including elements such as a title, input field for the city name, a button to trigger the fetch request, and a result section where the fetched weather data is displayed. The design focuses on simplicity and usability, ensuring that users can easily interact with the interface.

CSS is used to style the webpage, providing a visually appealing and responsive design. The color scheme uses gradients and smooth typography to create a modern, professional appearance. Elements such as rounded input boxes, hover effects on buttons, and a glass-like background for the result container make the interface aesthetically pleasing. Media queries ensure that the layout remains functional across various screen sizes, from desktops to smartphones, making the webpage fully responsive.

The real logic of the application is implemented using JavaScript. When the user enters a city name and clicks the “Get Weather” button, the script first calls a geocoding API to convert the city name into geographic coordinates (latitude and longitude). These coordinates are then passed to the Open-Meteo API to retrieve live weather information. The data is received in JSON (JavaScript Object Notation) format, which the script parses and displays on the webpage. Key weather parameters such as temperature, wind speed, and general conditions are shown in an easy-to-read format. Proper error handling is implemented to manage invalid inputs or network issues, ensuring the webpage provides meaningful feedback to the user in all cases.

This project not only demonstrates the technical process of integrating APIs but also highlights the importance of asynchronous programming using JavaScript’s fetch() method and Promises. Asynchronous operations allow the webpage to request and receive data from the API without reloading the entire page, providing a smoother user experience. Moreover, the task showcases the concept of data binding—the dynamic link between the API response and the elements displayed on the web interface.

In conclusion, this task serves as an excellent example of practical web development skills that combine design, logic, and data integration. It reflects how front-end developers can use APIs to transform static pages into dynamic, information-driven applications. Such projects build the foundation for more complex applications like weather dashboards, news aggregators, or IoT monitoring interfaces. Overall, the development of this webpage demonstrates creativity, technical understanding, and the ability to connect external data sources with front-end interfaces effectively—key skills in today’s web development environment.
