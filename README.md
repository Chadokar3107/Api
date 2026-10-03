# Api
<h2>Notes on api</h2>

An API (Application Programming Interface) is a set of rules that lets one piece of software talk to another. It defines what you can ask for, how to ask, and what you'll get back, without you needing to know how the other system works internally.

A common analogy is a restaurant. You (the app) don't walk into the kitchen. You give your order to a waiter (the API), who passes it to the kitchen (the server or system) and brings back your food (the response).

Example: A weather app on your phone doesn't collect weather data itself. It sends a request to a weather service's API, something like "give me today's forecast for Pune," and gets back structured data (usually JSON) that the app then displays.

```mermaid
graph TD
    App1[Weather App] -->|API Request| Server[Weather Server]
    Server -->|API Response| App2[Weather App]
```


The response might look something like:

{
  "city": "Pune",
  "temperature": 28,
  "condition": "Cloudy"
}

<b>Why do we need APIs?</b>
<p> Imagine you are building a food-delivery application.</p>
You need:
<ul><li>Maps 🗺️ </li>
<li>Online payments 💳</li>
<li>Restaurant information 🍔</li>
<li>SMS/OTP 📱</li>
<li>User authentication 🔐</li></ul>

