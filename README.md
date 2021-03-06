# AirBerlin App

## Current Flow
[https://marvelapp.com/18c2e21](https://marvelapp.com/18c2e21)

## Electronic Visa embedded in Flow

[https://marvelapp.com/8bcidhg](https://marvelapp.com/8bcidhg)

## APIs Info
This App uses the [AirBerlin API](https://app.xapix.io/airberlin) hosted on [XapiX.io](http://go.xapix.io/), and the [SimpleVisa API](http://www.simplevisa.com/developers). The AirBerlin API allows the creation of `passengers`, `credit cards`, `flight segments`, `customer addresses` and `bookings`. The SimpleVisa API allows the creation of `passports` and checks and create `electronic visas`.

## Inspiration
Frequent international travelers knows the struggle to get a travel visa for their destination: finding the correct visa, finding out where to apply, how to apply and what to answer to get approved is an unnecessary hassle.

## What it does
Integrating the SimpleVisa API into the current AirBerlin flow allows any traveler that book a flight ticket to apply for an electronic visa at the same time, if required.

## How I built it
I reproduced the current AirBerlin App flow and integrated an on-demand electronic travel visa API in the process.

## Challenges I ran into
The airline API was giving me errors when I tried to create a booking, so I simulated the last part of the booking process.

## What I learned
While I spoke to the AirBerlin team, I learned that the United States was a big market for the airline, so I focused the demo app on this specific destination country.

## What's next for AirBerlin-SimpleVisa-BusinessChallenge
Integrating the two APIs together was not too complicated, so I can see the concept extended to other destinations countries: wherever you travel to a destination country that requires an electronic visa, you can do it right from the AirBerlin app. Each visa have a different cost, so AirBerlin could include the price of the visa into the price of the flight, or offer the option to the user to process it for an additional cost.
