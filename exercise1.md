# Warming up
This answer looks at the case where
the language used is Java and the IDE is Eclipse.
the IDE is Eclipse


### Linter
One way is to configure Eclipse to format code every time it is saved. This can be set up in Eclipse with Window → Preferences → Java → Editor → Save Actions →
Check "Perform the selected actions on save"
Check "Format source code"


### Sharing lint settings
Preferences →Java → Code Style → Formatter
Here you can save a profile, export it, and share it with the team.


### Testing
JUnit testing. It is possible to do unit testing, as well as api testing.


### Building
In Eclipse: Right click file with main class → Export → Choose file type (for example jar) → Click next → Finish


Alternatively using the command line: mvn clean install


### Alternatives to Jenkins and GitHub Actions
TeamCity, CircleCI, Bamboo, GitLab, Buddy, Travis CI, Codeship, GoCD, Wercker, Semaphore, Nevercode, Spinnaker, Buildbot, Bitbucket Pipeline, Azure DevOps, Harness, IBM UrbanCode, Perforce Helix, GoCD, Integrity, Strider, Autorabit, Final builder, Buildkite, CruiseControl


### Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

I think the tools, the Eclipse built-in linter and JUnit testing along with a CI/CD workflo like GitHub actions are equally necessary whether the app is self-hosted or not. The size of the team (6 people) suggets that a cloud based setup would make more sense. Self-hosting will demand more human resources to set up and keep running, which is inconvenient for such a small team. Self-hosting may additionally take up more time to set up, which is also inconvenient considering the app is to be released soon.
