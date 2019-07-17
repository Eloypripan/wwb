# World War Bot

I stole the country data from https://github.com/lorey/list-of-countries
And also I use https://gadm.org/

The procedure works as follows:

        - Pick a random country
        - Pick a random neighbour of that country
        - Choose a probability of victory for the countries based on relative population
        - Choose a winner based on a random number choice and the calculated probability of victory
        - Transfer the loser's population and borders to the winner

    Repeat until only one country remains.
