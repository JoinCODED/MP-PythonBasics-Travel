1. Define a function called `hotel_cost` with one argument `days` as input. The hotel costs 40 KWD per night. So, the function `hotel_cost` should return `40 * days`.

2. Define a function called `plane_ride_cost` that takes a string, `city`, as input. The function should return a different price depending on the location. Below are the valid destinations and their corresponding round-trip prices.
   - Dubai: 50 KWD
   - Manama: 30 KWD
   - Doha: 35 KWD

3. Define a function called `rental_car_cost` with an argument called `days`. Calculate the cost of renting the car:
   - Every day you rent the car costs 10 KWD.
   - If you rent the car for 7 or more days, you get 15 KWD off your total.
   - Alternatively (`elif`), if you rent the car for 3 or more days, you get 10 KWD off your total.
   - You cannot get both of the above discounts.
   - Return that cost.

4. Define a function called `trip_cost` that takes two arguments, `city` and `days`. Have your function return the sum of calling the `rental_car_cost(days)`, `hotel_cost(days)`, and `plane_ride_cost(city)` functions.

5. Modify your `trip_cost` function definition. Add a third argument, `spending_money`. Add the variable `spending_money` to the sum that it returns.

6. Print out the `trip_cost` to **Dubai** for **5 days** with an extra **500 KWD** of spending money.
