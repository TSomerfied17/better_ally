# better_ally
This was my first Slack app attempt, following the instructions from this article: https://code.likeagirl.io/making-an-interactive-slack-app-part-1-d28fac5f996f#83e4

Below is copied her original README.

Tutorial for this app: https://medium.com/@sweetyclem/making-an-interactive-slack-app-part-1

Add environment variables
Add a .env file with these variables

Tunnel local ports
./ngrok http 5000

The events listen on /events The interactions listen on /interactions The command listen on /commands

Add the Ngrok URL to Slack settings
Run the app
npm run start
