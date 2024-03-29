# Soccer Management System
In this homework, implement a simple Soccer Management System that will be used by the Turkish Football Federation (TFF). TFF organizes 11 football leagues: Super League, 1. League, 2. League, 3. League, A2 League, Amateur League, Women's League, Development League, Beach Soccer League, Futsal League, and Turf League. Especially, the program will help to manage the Super League. This league has 21 teams and 630 players. \
\
The program should allow a user to manage a number of teams and keep the match statistics. The program has to include some entities to handle the records of soccer teams, players, coaches, matches, stadiums, referees, sponsorship companies, etc.\
\
A team is represented with several attributes, including name, foundation year, number of cups, and two main colors. \
\
Each team has a coach who manages the team within a period, starting from the contract date to the end date, and earns a salary (monthly). When needed, to be able to communicate with a coach, his contact information (address, phone) should be kept in the system. \
\
Each player should be represented with basic features such as license number, name surname, birthdate, nationality, address, and phone. Each player belongs to a team within a period, starting from the contract date to the end date, and earns a salary. The main positional role of a player should also be kept in the system, including goalkeeper, defender, midfielder, or attacker. \
\
Each match is controlled by a referee, who is assisted by two assistant referees. When needed, to be able to communicate with a referee, his contact information (address, phone, etc.) should be kept in the system. \
\
In a match, the home-team will play with the away-team. If a team wins a match, it is awarded 3 points. If a team draws a match, it is awarded 1 point. If a team loses a match, it is not awarded any points. The program should read an input file to get the results of the matches that have been played. \
\
Football matches have been played in stadiums and there are approximately 60 stadiums in different cities in Turkey, with different capacities and lighting options (available or not). They have different surface types such as grass, soil, etc. \
\
Currently, each football team has one sponsor. For example, some sponsorship companies are Ülker, Türk Telecom, and Vodafone. Sponsorship information should also be stored in the system such as company name, company address (formatted as street, town, city, country), and phone number (formatted as country code + area code + number). \
\
Entities in the system (i.e., team, coach, company, referee) have ID properties to identify each record. All IDs must be incremented automatically.
