# F1-web-service
CW2 webdev assigment 

This is the backend of the our F1 tracker web api service.
The backend dependencies:
  - Written in typescript (ts)
  - Supabase database (db)
  - Internal server with Deno
# user stories
  - I am a possible user of the F1 web service, I want to be able to create a profile that lets me store my favourite race track and drivers
  - I am a F1 fan and want to be press a button have a reminder (call `/race/next`) to able to see the name, circuit, and session start times of the next Grand Prix
  - As a data analyst I want /laps/fastest?race_id={id}  so that I can download a JSON table of each drivers fastest lap for a given race
  - As a strategist I want /compare/average-lap?d1=11&d2=22$race_id={id}  so I can compare the average speed within a given race of two drivers
  - As a new fan I want to be able to /drivers/{driver_id}  to show me a bio, portrait, and the career stats so I can learn about a given driver
  - As a fantasy-league player I want to be able to post my email to /alerts  so that I get notified by email when a pit-window opens in the next race
  - As a user, I want to be able to create an account in the an F1 tracker web service
