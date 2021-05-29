# The Family Drive-in Theatre

Presently, website is very basic and previous website was not quite as modern. This is a personal project to tackle the challenge of The Family Drive-in Theatre to build a more stronger web presence for fans and movie lovers.

## Conceptual Site Map

- Movies
  - Movie tickets
- Live Concerts
  - Live concerts tickets
- About Us 
  - [Google Maps](https://developers.google.com/maps/apis-by-platform) or [MapBox](https://docs.mapbox.com/api/overview/) APIs for customized direction
  - History of The Family Drive-in Theatre
  - Movies archive
  - Live Concerts archive
- Concession
- Contact

## Administrator Access

- CRUD Movies w/ [**_OMDB API_**](https://www.omdbapi.com/)
  - Searcheable movie database
  - Movie posters
  - Movie synopis
  - Movie rating
  - Screen #
  - Showing time
  - Day of Week
  - Bonus (if applicable)
- [**_The New York Times Movie Reviews API_**](https://developer.nytimes.com/docs/movie-reviews-api/1/overview)
  - Movie reviews (if applicable)
- CRUD Live Concerts
  - Band posters
  - Band description
  - Screen #
  - Concert time
  - Day of Week
  - Bonus (if applicable)
- CRUD Concessions
  - Image
  - Description
  - Pricing
  - Stock/Out of stock
  - Seasonal special (if applicable)
  - Bonus (if applicable)
- CRUD Everything else - adopt CMS approach

## Membership Access

- Recieve alerts on movies/live concerts
  - Optionally turn on/off each alerts
  - Optionally choose between text/email
- Keep record of purchase history

## Ticket Purchases

- Movie tickets
  - Single purchase per vehicle
  - Single purchase per person
  - Season pass

- Live Concert tickets
  - Single purchase per vehicle
  - Single purchase per person

- Payment processing [Stripe API](https://stripe.com/docs/api)
