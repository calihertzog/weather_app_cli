This weather app operates in the command line interface (CLI). It conveniently displays the weather condition and temperature, in Celsius or Fahrenheit, for the user-provided city. The weather is accessed through OpenWeather's services.

The user inputs a city. In this example, the city is Los Angeles.

<img width="335" alt="Screenshot 2023-04-15 at 9 18 04 PM" src="https://user-images.githubusercontent.com/127066402/232266306-06531ef0-0ffe-4ccc-80c3-77216a7642a9.png">

<img width="467" alt="Screenshot 2023-04-15 at 9 18 36 PM" src="https://user-images.githubusercontent.com/127066402/232266317-cd07acb2-6f7d-4cd5-9e8e-919fbcc09d15.png">

Celsius is the default unit of temperature. If the user wants Fahrenheit, they add the "-i" tag to display the temperature in imperial form.

<img width="346" alt="Screenshot 2023-04-15 at 9 19 37 PM" src="https://user-images.githubusercontent.com/127066402/232266333-7a327576-a312-4fc9-940b-34890b96bf2a.png">

<img width="467" alt="Screenshot 2023-04-15 at 9 19 11 PM" src="https://user-images.githubusercontent.com/127066402/232266339-d3327713-0494-4891-8f78-ed64195b992e.png">

If the user provides an invalid city name, or one that OpenWeather does not have data on, a message will be printed and the user will have to run the program again using a valid city.

<img width="272" alt="Screenshot 2023-04-15 at 9 15 58 PM" src="https://user-images.githubusercontent.com/127066402/232266136-39e60ab8-af1d-43e0-8431-5fe299f99056.png">

The colors of the weather condition output are dependent on the condition: blue for rain, red for thunderstorm, yellow for clear, and more.  A matching weather themed emoji is also printed.  
