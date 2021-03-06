## API week project

Your project this week is to build a simple web app (ideally just a single page). You must query an API and use the result to update the DOM.

What you choose to build and how you choose to display the data is entirely up to you!

During the planning phase we suggest you spend time on:

* Exploring APIs you are interested in working with
* Considering your user journey
* Deciding what you need to build for your Minimum Viable Product (MVP) and splitting up the tasks

You'll have most of day 3 and all of day 4 to work on your project. On day 5 we'll have code reviews in the morning and final presentations in the afternoon.


### Choosing your APIs

See our list of recommended APIs [here](./recommended-apis.md).

You can choose to use other APIs if you prefer, but make sure to do your research and check that what you want to do with the API is possible before you start to code.

#### Things to check before you start:
* Are there issues with CORS requests?
* Is there a high enough rate limit?
* Is a free API key available?
* Are you able to use the API without user authentication (oAuth)?
* Is good documentation available?


### Requirements

* Your app queries APIs using the fetch() method
* Your app features some dynamic content
* A clearly defined user journey, documented in your readme.
* A well-considered architecture for your app - think back to the workshops from the beginning of this week. Try to modularise your code, or break it down into separate files. Document any key decisions about how you structure your code in your readme!
* User stories in issues!
* Code: break your JavaScript down into small functions with a clear input and output; this will make it easy to write tests
* Design: aim for a responsive, mobile-first design
* Accessibility: same as always, we'll be running your code through accessibility checkers
* Take appropriate measures when it comes to [concealing private information](https://gist.github.com/derzorngottes/3b57edc1f996dddcab25) (i.e. your API key!)

#### Stretch Goal

* Query a second API!

### Keep in mind

* If using a private API key, you won't be able to deploy to GitHub pages this week (if you're not using an API key, go for it!)
* Don't repeat yourself! Try to reuse and refactor bits of existing code where possible.
* Minimise DOM manipulation to keep your app efficient
