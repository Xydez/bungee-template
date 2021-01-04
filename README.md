# bungee-template
bungee-template is a template repository for developing BungeeCord plugins.

To get started, git clone the repository. Change the group property in build.gradle. Change the project name in settings.gradle. Finally, build the project.

    $ gradlew build

To deploy the project you need to uncomment the deploy task in build.gradle and change the path to your plugins folder, then deploy the jar.

    $ gradlew deploy
