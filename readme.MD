# uowbo!
Fast, easy and secure set of tools for University of Westminster Discord servers to crowd-control members, improve security and relax moderation.

## Do I need it?
Depending on your current setup, you may or may not need to use uowbo! in your server.
- I am a society who manually verifies members
  - You can use uowbo! to replace all that effort and have members verify themselves
- I am a Discord server for other people on the same course as me
  - You can use uowbo! to prepare yourself in the event of an unexpected raid

## Features
uowbo! is constantly expanding and gaining more features every few weeks to help server owners and moderators stay on-top of their moderation. At the moment uowbo has support for the following features.

|Legend|Meaning|
| -------- | ------- |
|✅|Out now - the feature is now available everywhere|
|🚧|Beta testing* - the feature is available to certain server owners|
|💥|Upstream - the feature is being finalised and will be tested soon|
|✏️|In development - the feature is currently being built|
|💤|Planned - the feature is planned and on the roadmap|

- ✅ Students can verify themselves using their university email address
- ✅ Students can verify themselves using their university ID card
- ✅ Externals can verify themselves
- ✅ Multiple servers can use the same uowbo! instance at the same time


## Development
If you want to aid development of uowbo! by contributing, follow these steps to get you started.
### Prequisites
- Git
- Node.js
- A Discord server
- (optional) mailing server

### Setting up the repository
In your terminal, clone the repository using:

```
git clone https://github.com/ejaz4/uowbo
```

This will pull the latest source of uowbo and two submodules, these submodules might not usually be pinned to the latest commit of their repository. As you are developing, `cd` into whichever submodule you want to work on, create a new branch using the name scheme: `type/description`.

In each submodule folder there is a `.example.env` file that must be filled and copied to `.env`. If you add a new key-value pair, you must also add it to the `.env.example` in the mono-repo as well and in the `docker-compose.yml` file.

In each of the repositories, run `yarn` to install all the dependencies.

