# Running the project

## Required:

- .env file (with ACCESS_TOKEN_SECRET and REFRESH_TOKEN_SECRET variables)

ACCESS_TOKEN_SECRET=976a66a5bd23b2050019f380c4decbbefdf8ff91cf502c68a3fe1ced91d7448cc54ce6c847657d53294e40889cef5bd996ec5bd996ec5b0fefc1f56270e06990657eeb6e

REFRESH_TOKEN_SECRET=5f567afa6406225c4a759daae77e07146eca5df8149353a844fa9ab67fba22780cb4baa5ea508214934531a6f35e67e96f16a0328559111c597856c660f177c2

- mysql database (edit the ormconfig.json)

## Run migration with:

```
npm run typeorm migration:run
```

## API End-Points

- /auth/login
- /auth/check
- /auth/logout
- /auth/signup
- /polls/
- /polls/start
- /polls/status
- /polls/end
- /polls/reset
- /polls/voters
- /polls/vote
- /users/all
- /users/verify
- /users/delete/:id
