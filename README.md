This tests are checking that:

- A GET request to the / address returns the string 'Hello, world!' and the correct status.
- A POST request to the /users address returns a JSON object with user data and the correct status indicating that the user has been created.
- The response body message contains the text "success"
- The value of response.body.data.isDeveloper is true
- The value of response.body.data.followersOnGithub is greater than 10

 1. Add dependencies with the `npm install` command
 2. Run tests with `npm run test`
