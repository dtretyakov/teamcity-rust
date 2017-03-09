# TeamCity Rust Plugin

<a href="https://teamcity.jetbrains.com/viewType.html?buildTypeId=TeamCityRustPluginBuild&guest=1"><img src="https://teamcity.jetbrains.com/app/rest/builds/buildType:(id:TeamCityRustPluginBuild)/statusIcon.svg" alt=""/></a>

The TeamCity Rust plugin brings build infrastructure support for the [Rust](https://www.rust-lang.org/) programming language.

# Features

It provides the following features for Rust projects:
* Rust toolchains installation via [rustup](https://www.rustup.rs/)
* Cargo command build runners
* Cargo tests reporter
* Structured build log listener
* Auto-discovery of build steps
 
# Download

You can [download the plugin](https://plugins.jetbrains.com/plugin/9044) and install it as [an additional TeamCity plugin](https://confluence.jetbrains.com/display/TCDL/Installing+Additional+Plugins).

# Compatibility

The plugin is compatible with [TeamCity](https://www.jetbrains.com/teamcity/download/) 9.1.x and greater.

# Build

This project uses gradle as the build system. You can easily open it in [IntelliJ IDEA](https://www.jetbrains.com/idea/help/importing-project-from-gradle-model.html) or [Eclipse](http://gradle.org/eclipse/).

# Contributions

We appreciate all kinds of feedback, so please feel free to send a PR or submit an issue.
