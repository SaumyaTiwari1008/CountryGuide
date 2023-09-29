# CountryGuide


The key feature of this project is a search functionality, allowing users to input queries, likely the names of different countries. Upon receiving this input, the application triggers a request to a RESTful API, which is designed to provide basic information about countries.

The API adheres to the principles of REST, utilizing standard HTTP methods such as GET to perform operations on resources, in this case, countries. The returned data is typically in JSON format and includes details like country name, capital, population, currency, languages spoken, among other attributes.

The interaction flow is as follows: when a user submits a query, the JavaScript code captures this input and constructs an HTTP request to the designated API endpoint for country queries. Subsequently, the API processes the request and responds with relevant data. The JavaScript code then processes this data and updates the DOM to display the information about the queried country.

![Screenshot 2023-09-30 002423](https://github.com/SaumyaTiwari1008/CountryGuide/assets/131397199/5a5d82b5-20aa-4801-9d74-043d279ec930)
![Screenshot 2023-09-30 002530](https://github.com/SaumyaTiwari1008/CountryGuide/assets/131397199/793cad66-ee15-484b-8b95-99a3d865f5e6)
![Screenshot 2023-09-30 002601](https://github.com/SaumyaTiwari1008/CountryGuide/assets/131397199/5787d527-6790-498c-ba94-e42cfd2c4d41)



The project also incorporates error handling to account for scenarios where the API request may fail or the user enters an invalid query. Additionally, once the API responds with data, the JavaScript code formats it and updates the HTML elements to present the information in a user-friendly manner.
![Screenshot 2023-09-30 002629](https://github.com/SaumyaTiwari1008/CountryGuide/assets/131397199/4bf4741e-8434-4feb-a1d4-e3231cc7309b)
![Screenshot 2023-09-30 002653](https://github.com/SaumyaTiwari1008/CountryGuide/assets/131397199/9dd5ddae-a5a7-4495-a4cd-82a536aa9c61)



Overall, this project showcases a seamless integration of frontend technologies and a RESTful API, resulting in an application that empowers users to effortlessly search for and retrieve basic information about various countries through a user-friendly web interface.
