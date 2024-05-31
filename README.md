# Learning in public

This is an experiment.  On May 1, 2024, I said I was willing to help.  Eunice was ready to learn.
I had an idea of how I could help.  Eunice agreed to take a chance.
I had some conventions in my head. I had infrastructure and code mostly ready to go, from the work I do while streaming and practicing.
Eunice asked me "Why are you doing this for free, what's in it for you?"

"Lift as we climb!"

In order to make this more successful, I figured that we should document the journey.
I'm doing the onboarding for Eunice, and Eunice will do the onboarding for the next person, and that will continue as needed.

It starts here. This is how things are going to work from here forward.

## So what is it?

I'm providing a "platform" for you to deploy your Spring Boot applications.
My platform is built with "Raspberry Pi" devices, which are ARM64 single board computers (SBC).
I'll provide the things, that software engineers get from their platform teams, in the enterprise, but with "homelab grade" service level agreements (SLA).
We will learn together.

The goal is for you to have something "in production" that you have built, that you understand, that you maintain.

## What do I do?

- You have to show up for the community
- You will have to submit a "pull request" first, updating the Bootiful list below.
- Onboarding is at the discretion of the person doing the onboarding, and me.

## Learn by teaching

I have some resources, that I would like to share. I have some ideas and experience, that I would like to share. I believe that this will help people learn, more, faster, and stickier.
Everything is "public" on purpose.

## Milestone 1

- Register the `.org` domain name: mydomain.org
- Create the GitHub Organization: mydomain-org
- Create the Gateway Service Repo: org.mydomain.service.gateway
- Use [start.spring.io](https://start.spring.io) to create the application: Maven, Java 21, with dependencies: GraalVM, Reactive Spring Cloud Gateway, Actuator

## Milestone 2
- Install [Spring CLI](https://docs.spring.io/spring-cli/reference/installation.html)
- In the root of your project, Install CLI commands `spring command add --from https://github.com/dashaun-project-catalog/commands`
- `spring extensions add`
- Tag the repo: `git tag v0.0.1`
- Push the tag: `git push origin v0.0.1`
- Create the `flux` repository
- Add `kustomization.yaml` and `org.mydomain.service.gateway.yaml` to the `flux` repository
- (wait)
- Validate: https://mydomain.org/actuator/health status == "up"

## Bootiful Path To Production

Create a `pull request` adding your name to the first column.
The other 2 columns will be updated during onboarding.

| My GitHub | Onboarded by | Production |
|-----------| ------------ | ---------- |
| [DaShaun](https://github.com/dashaun) | [DaShaun](https://github.com/dashaun) | [javagrunt.com](https://javagrunt.com) |
| [Eunice](https://github.com/eunix56) | [DaShaun](https://github.com/dashaun) | [euniceb.org](https://euniceb.org) |
| [Manuel](https://github.com/manuelinfosec) | 
| [Jiggabyte](https://github.com/jiggabyte) | 
| [Korede](https://github.com/Kordedekehine) |
| [Ifeanyichukwu](https://github.com/ifeanyichukwuOtiwa-sports)|
| [Oluwafemi](https://github.com/Oluwafemijohn1)|
| [Chukwuemeka](https://github.com/Charlyco)]


