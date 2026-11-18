# Google OAuth Express Server

Google OAuth 2.0 authentication server using Express and Passport.js.

## Dependencies

Install the required packages:
```bash
npm install
```
(Requires `express`, `passport`, and `passport-google-oauth20`)

## Configuration

Add your Google Cloud Console OAuth 2.0 credentials in [index.js](file:///Users/cheng/Desktop/Oauth%20setup/index.js):
- `ClientID`
- `ClientSecret`

Authorized redirect URI in Google Cloud Console:
```
http://localhost:3003/callback
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

Server will run on [http://localhost:3003](http://localhost:3003).
# OAuth-setup
