# Setup Instructions for WordPress Content Automation

## Installation Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/akankwatsa1/wordpress-content-automation.git
   cd wordpress-content-automation
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

## Environment Setup
- Ensure you have Node.js (version 12 or higher) and npm installed on your machine.
- You can check your Node.js and npm version with:
   ```bash
   node -v
   npm -v
   ```

## API Key Configuration
1. Obtain your API keys from the respective service provider.
2. Create a `.env` file in the root of the project.
3. Add your keys to the `.env` file:
   ```plaintext
   API_KEY=your_api_key_here
   ```

## WordPress Setup
1. Install WordPress in your local environment or a web server.
2. Set up a new database for your WordPress installation.
3. Configure the `wp-config.php` file with your database details:
   ```php
   define('DB_NAME', 'database_name_here');
   define('DB_USER', 'username_here');
   define('DB_PASSWORD', 'password_here');
   define('DB_HOST', 'localhost'); // Probably localhost
   ```

## Database Setup
1. Use MySQL or phpMyAdmin to create the necessary database.
2. Run the following command to create required tables, if applicable:
   ```sql
   CREATE TABLE ...;
   ```

## Local Development Guide
- Use a local server like XAMPP, MAMP, or Local by Flywheel to run WordPress.
- For debugging, consider installing the Query Monitor plugin.
- Follow best practices for local WordPress development, including using version control (git) and keeping plugins and themes updated.

Happy developing!