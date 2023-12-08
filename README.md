
# Creative Deal Analysis Project

## Installation Guide

Follow these steps to install the Creative Deal Analysis project:

0. Clone this project using the following command:
   ```bash
   git clone git@github.com:hafizsiddiq7675/de-calculator.git

1. Navigate to the project directory:
   ```bash
   cd creative-deal-analysis
   
2. Run the following command to install project dependencies:
   ```bash
   composer update

3. Copy the provided `env.example` file to `.env` and set the required credentials:
   Email credentials
   Vonage Credentials
   Google API Credentials

5. Set the database name in the `.env` file.

6. Generate an application key by running the following command:
   ```bash
   php artisan key:generate

7. Run the database migrations and seed the database:
   ```bash
   php artisan migrate --seed
   
8. Start the Laravel development server:
   ```bash
   php artisan serve
   
9. Access the project on http://localhost:8000 in your web browser.
