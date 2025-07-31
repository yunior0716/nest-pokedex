<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="120" alt="Nest Logo" /></a>
</p>

# Run in development

1. Clone the repository
2. Install dependencies
   ```
   yarn install
   ```
3. Install nest cli globally
   ```
    npm i -g @nestjs/cli
   ```
4. Deploy the database

   ```
   docker compose up -d
   ```

5. Clone the environment file **.env.example .env** and rename to **.env**

6. Fill the environment variables in the **.env** file

7. Run the application

   ```
   yarn start:dev
   ```

8. Seed the database
   ```
   http://localhost:3000/api/seed
   ```

## Used stack

- NestJS
- MongoDB
- Docker
