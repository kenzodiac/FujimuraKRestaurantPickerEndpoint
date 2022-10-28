# FujimuraKRestaurantPickerEndpoint
Kenneth Fujimura

Last Revised: 10-27-2022

Program Description: This is a program that emulates the console project of the same name that we did during the coding combine. It's an API program that takes in a string input from the user, and uses a random number generator to give the user a suggestion for a place to eat. The input decides whether to narrow down the suggestions to specific categories of restaurants, depending on the user's preference.

Peer Review By: Daniel Decoito - The api and code work really well, the assignment meats all criterira. I really the use of data validation for this project and the way the arrays are organized.

How To Instuctions:
1) Load the program into VSCode.
2) Start Debugging.
3) Copy Local Host URL from the console (e.g. "http://localhost:5264")
4) Open Postman program and paste the copied URL into a new workspace, with the "GET" input field.
5) Append the URL with "RestaurantPickerEndpoint/RestaurantPicker/{category}"
6) Replace "{category}" with one of the numbers between 1-4. Seelcting "1" narrows the restaurants down to only restaurants in Lodi, CA. "2" selects restaurants from Stockton, CA. "3" selects Fast Food. "4" will pick from all three categories. Once an input is selected, hit the "Send" button to the right of the input field.
