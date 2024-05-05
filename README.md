# GitHub Resume Generator

This project is a web application that generates a professional resume from a GitHub profile. Simply enter a GitHub username, and the application will create a resume based on the user's contributions and projects.

## Features

- Fetches user data from GitHub's API
- Generates a professional resume based on GitHub contributions and projects

## Screenshot

![image](https://github.com/ashutosh-rath02/git-re/assets/85403534/13ae316c-2254-4da3-b07f-8b55924a9b98)

## Mentions

The contribution graph in the user profile is generated using [ghchart](https://ghchart.rshah.org/) by [Rushi Shah](https://github.com/2016rshah). This service creates an image of a user's GitHub contribution graph which can be embedded in a webpage.

## Setup and Installation

1. Clone the repository to your local machine.
2. Install the dependencies using `npm install` or `yarn install`.
3. Start the development server using `npm run dev` or `yarn dev`.
4. For authentication, we have used Github OAuth using Supabase. To set this up:
   - Go to your [Supabase Dashboard](https://supabase.io/dashboard).
   - Select your project / Create a new one.
   - Navigate to the "Authentication" section, then to the "Settings" tab.
   - Under "OAuth Providers", find GitHub and fill in the "Client ID" and "Secret" fields with the details from your GitHub OAuth App. If you haven't created a GitHub OAuth App yet, you can follow [this guide](https://docs.github.com/en/developers/apps/building-oauth-apps/creating-an-oauth-app).
   - Save your changes.
   - Now you can do the authentication using github
5. Copy the `.env.example` to `.env.local` and put the secrets.
6. You are gtg.

## Tech used

- NextJS 14
- Shadcn/ui
- Tailwind CSS
- Github public API

## Upcoming features🎉

- Add Supabase authentication
- Comparison between users
- Resume templates

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you would like to help improve the project.

## License

This project is licensed under the Apache 2.0 License & all rights reserved to author [ashutosh-rath02](https://github.com/ashutosh-rath02)
