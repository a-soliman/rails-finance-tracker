# finance-tracker
*Rails7 Finance tracker application*

## Ruby version
- 3.2.1

## System dependencies
- Ruby 3.2.1
- Rails 7
- NodeJS 18.14.2
- npm 9.5.0
- yarn 1.22.11

## Setting credentials

*code in `"code --wait"` is for VSCode, exchange it with your editor of choice*

```bash
EDITOR="code --wait" rails credentials:edit
```

```yml
polygon:
  api_key: "YOUR_KEY"
```

## Development
1. install dependencies `bundle install`
2. install node dependencies `npm i`
3. migrate/prepare the database `rails db:migrate`
4. run the development server `./bin/dev`

## Database initialization
``` bash
rails db:migrate
```

## How to run the test suite
```bash
rails test
```

## Deployment instructions
``` bash
git push heroku main
heroku run rails db:migrate
```
