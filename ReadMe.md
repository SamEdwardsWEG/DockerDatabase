# Sql Server 2017 instance running in Docker

## How to use for first time
1. Clone this repository to your machine.
2. Open terminal and navigate to Docker Database folder
3. Add a file called '.env'
4. Inside the .env file add a line following the below convention
    4.1 SA_PASSWORD=YourSuperSecretPassword
5. Run `docker-compose up -d`.
    5.1 If you get a pop up asking to share your folder then click "Share It".
6. Ammend connection strings to include `Data Source=localhost, 1433`, `User Id=SA`, `Password=YourSuperSecretPassword`.

When you've finished you can bring to container down if you wish with `docker-compose down`. This will keep all data so when you bring the container back up your databases will still be there with all your data.

## Bringing the container back up
1. Open terminal and navigate to Docker Database folder
2. Run `docker-compose up -d`.
3. Ammend connection strings to include `Data Source=localhost, 1433`, `User Id=SA`, `Password=YourSuperSecretPassword`.
