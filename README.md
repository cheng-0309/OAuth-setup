# Google OAuth Express Server

Google OAuth 2.0 authentication server using Express and Passport.js.

## Dependencies

Install the required packages:
```bash
npm install
```
(Requires `express`, `passport`, and `passport-google-oauth20`)

## Configuration

Configure your Google Cloud Console OAuth 2.0 credentials in `.env`:
- `CLIENT_ID`
- `CLIENT_SECRET`
- `PORT=3031`
- `REDIRECT_URI=http://localhost:3031/callback`

Authorized redirect URI in Google Cloud Console:
```
http://localhost:3031/callback
```

## Running the Server

- **Start server**:
  ```bash
  npm start
  ```
- **Development mode (auto-reload)**:
  ```bash
  npm run dev
  ```

Server will run on [http://localhost:3031](http://localhost:3031).
