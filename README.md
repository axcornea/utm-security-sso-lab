# Security course SSO lab (#6)

The main goal of this lab consists of implementing an application letting a user log in using three different social login providers and showing available account information.

## Running locally

### Prerequisites

To run this application locally use need to have the following tools installed on your workstation:
* JDK 11+ (OpenJDK used during development)

### Configuration

This application integrates with the Auth0 login provider, which you have to configure before running the app. Please consult Auth0 documentation in order to set up your account and a new app. Feel free to set up any social providers that you want.

After a successful Auth0 app configuration, fill the following variables inside the `src/main/resources/application.yml` file:

* `client_id`
* `client_secret`
* `issuer_uri`

You can find values for those variables on the Auth0 app page.

### Running

Run the following command inside the root of this repository:

```bash
# *nix
> ./gradlew

# Windows
> .\gradlew.bat
```

The application will start in a few seconds and will be accessible under `http://localhost:8080/` web page.

## Demo

<div style="padding:56.25% 0 0 0;position:relative;"><iframe src="https://player.vimeo.com/video/650166115?h=d44a475d2d&amp;badge=0&amp;autopause=0&amp;player_id=0&amp;app_id=58479" frameborder="0" allow="autoplay; fullscreen; picture-in-picture" allowfullscreen style="position:absolute;top:0;left:0;width:100%;height:100%;" title="2021-11-26 05-50-54.mkv"></iframe></div><script src="https://player.vimeo.com/api/player.js"></script>