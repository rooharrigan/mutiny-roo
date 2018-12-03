
# To run locally
1. git clone this repo and `cd` into it
2. install ngrok and run `ngrok http 3000`
3. run `npm start`
4. Verify the app is running on `localhost:3000/`
5. postman to `ngrok.whatever.io/routes` with appropriate params to see the post routes

# Feedback on this challenge
1. The names of the page_view events are inconsistent (one has the noun `event`, and one only has the descriptor of the noun). Recommendation, remove the noun in both cases.
2. The first example request body for the track API is in the shape of a page_view event, but is missing the required key `elapsed_time_in_ms`.