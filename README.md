Run with: `npm run dev`

Important Notes:

- Refresh tokens are valid for 180 days
- Access tokens are valid for 2 hours

- We can have a retry mechanism that refreshes the access token if the API call fails due an authentication error.
- Note that when refreshing the access token, you will get a new refresh token which you must use when fetching your next access token.