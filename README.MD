# BIGBANG JAVA DEVELOPER MACHINE SCRIPT

This script installs and configures the essentials tools to create apps with Java Platform on Ubuntu 18.04 or 20.04.
> You can use this script, without the '--with-gui' option, to configure the tools inside Windows WSL 2 or as a Vagrant provisioning script file.

Clone or download this repo and then run the boom script this way.

```bash
./boom
```
> You have to restart your machine to finish the installation

To check the detailed logs:
```bash
tail -f -n 1000 logs/bigbang.log
```

### The script installs these tools by default:

|  Tool                 | Version                                  |
|--|--|
| Java JDK              | latest AdoptJDK 11 & 8 on sdkman         |
| Maven                 | Latest on sdkman                         |
| Ant                   | Latest on sdkman                         |  
| NodeJS                | 10.19.0                                  |
| Yarn                  | 1.22.4                                   |
| React                 | 3.4.1                                    |
| Git                   | 2.25.1                                   |
| Docker                | 19.03.10                                 |
| Docker Compose        | 1.25.5                                   |
| ZSH with OhMyZsh      | latest                                   |


Run this command if you need GUI tools as well

```bash
./boom --with-gui
```

To install only the gui tools:
```bash
./boom --only-gui
```

### The script installs these tools:

|  Tool                 | Version                  |
|--|--|
| Visual Studio Code    | 1.45.1                   |
| Eclipse               | 2020-03-R                |
| Intellij IDEA         | 2020.1.1                 |
| Google Chrome         | 83.0.4103.61             |
| Postman               | latest from snap         |
| VisualVM              | 2.0.2                    |
