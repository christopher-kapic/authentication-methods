# Authentication Methods

A collection of options for how you can handle user authentication in your applications.

If you would like to add an authentication method, check out `CONTRIBUTING.md`.

## Self-hosted
- [GoTrue (Netlify)](https://github.com/netlify/gotrue)
- [GoTrue (Supabase)](https://github.com/supabase/gotrue)
- [Keycloak](https://www.keycloak.org/)
- [FusionAuth](https://fusionauth.io/)

## Open source
- [GoTrue (Netlify)](https://github.com/netlify/gotrue)
- [GoTrue (Supabase)](https://github.com/supabase/gotrue)
- [Keycloak](https://www.keycloak.org/)

## Third party
- [Firebase](https://firebase.google.com/docs/auth/)
Free for unlimited users (rate limits eventually). [Read more](https://github.com/christopher-kapic/authentication-methods/blob/main/reviews/firebase.md).
- [Amazon Cognito](https://aws.amazon.com/cognito/)
Free for the first 50,000 users.
- [Okta](https://www.okta.com/)
Free for the first 15,000 users.
- [Supabase Auth](https://supabase.io/docs/guides/auth)
Free for the first 10,000 users. [Read more](https://github.com/christopher-kapic/authentication-methods/blob/main/reviews/supabase.md).
- [Userfront](https://userfront.com/)
Free for the first 10,000 users.
- [Auth0](https://auth0.com/)
Free for the first 7,000 users.
- [Netlify Identity](https://docs.netlify.com/visitor-access/identity/)
Free for the first 1000 users.

# Pricing
_Note: As I am preparing this chart, it is glaringly obvious that Auth0 is a bad choice for public applications (maybe it is better for internal business applications, but that is not exactly the point of this analysis). Do not use Auth0._

| Price     | Firebase       | Cognito      | Supabase     | Userfront    | Auth0        | Okta | Netlify Identity   |
| :-------- | :------------: | :----------: | :----------: | :----------: | :----------: | :--: | :----------------: |
| $0/month  | Unlimited      | 50,000       | 10,000       | 10,000       | 7,000        |15,000| 1000               |
| $25/month | Unlimited      | 54,545       | 100,000      | 10,000       | ?            | ?    | 1000               |
| $75/month | Unlimited      | 63,636       | Unlimited    | 10,000       | ?            |  ?   | 1000               |
| $100/month| Unlimited      | 68,181       | Unlimited    | 10,000       | ?            |   ?  | Unlimited          |
| $140-160/month| Unlimited  | 75,454-79,090| Unlimited    | 50,000       | ?            |   ?  | Unlimited          |
| $275/month| Unlimited      | 100,000      | Unlimited    | Special use case | ?        |    ? | Unlimited          |


## Yet-to-review
There are several options which I have discovered but not yet researched.
- [Frontegg](https://frontegg.com/user-management)
- [Ory](https://www.ory.sh/open-source)
- [Authelia](https://www.authelia.com/)
- [Gluu](https://gluu.org/)
- [Barong](https://github.com/openware/barong)
- [PrivacyID3A](https://www.privacyidea.org/)
- [SuperTokens](https://supertokens.io/)
- [Django](https://www.djangoproject.com/)
- [NextJS Auth](https://next-auth.js.org/)
- [SailsJS](https://sailsjs.com/)
- [AdonisJS](https://adonisjs.com/)
