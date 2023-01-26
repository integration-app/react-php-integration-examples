# Php + React Integrations Page example

Complete code example of displaying list of external apps that your users can connect to. The connection can then be used to run integrations.

## Installation

### Backend
- `cd backend`
- `composer install`
- Replace `{WORKSPACE_KEY}`, `{WORKSPACE_SECRET}` with ones from https://console.integration.app/settings/access in `./integrationAppToken.php`
- (optionally} Fill wanted user data in the same file

### Frontend
- `cd frontend`
- `npm install`

## Run
- Run backend: `php -S localhost:8080` in `backend` folder
- Run frontend: `npm run start` in `frontend` folder