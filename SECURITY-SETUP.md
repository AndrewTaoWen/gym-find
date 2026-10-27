# Security deployment changes

Revoke the previously committed RapidAPI credential. Set REACT_APP_RAPID_API_KEY in a local environment file for development. Client-side build variables are public; production calls requiring a private API credential must move behind an authenticated backend.
