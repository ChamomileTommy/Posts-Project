
# Post Project

Project to show Posts and Comments, Sign in with OAuth

## PostgreSQL DB

To create PostgreSQL DB:
- Go to https://railway.app/ 
- Click "Start new project"
- Click "Provision PostgreSQL"
- Copy DATABASE_URL

![My Image](PostgreSQL.png)

## Github OAuth 

To generate  GITHUB_ID and GITHUB_SECRET:
- Go to your Github
- Choose settings/Developer settings/Outh Apps/New OAuth App
- Register a new OAuth application
- Copy GITHUB_ID and GITHUB_SECRET

![My Image](github.png)

## Run Locally

Clone the project

```bash
  git clone https://github.com/ChamomileTommy/Posts-Project.git
```

Go to the project directory

```bash
  cd Posts-Project
```

Install dependencies

```bash
  npm install
```

Config .env

```bash
  DATABASE_URL=""
  GITHUB_ID=""
  GITHUB_SECRET=""
  GOOGLE_CLIENT_ID=""
  GOOGLE_CLIENT_SECRET=""
```

Create tables for PostgreSQL DB

```bash
  npx prisma migrate dev
```

Start the server

```bash
  npm run dev
  #Run on http://localhost:3000/
```


## Demo

![My Image](demo.png)

## 🚀 About Me
I'm a full stack developer for 4 years
