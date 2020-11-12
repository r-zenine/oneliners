# oneliners
My personal configuration for [r-zenine/ssam](https://github.com/r-zenine/ssam)

## Available commands: 

| Tool     |   command              | decription                                                         |
|----------|------------------------|--------------------------------------------------------------------|
| pass     | password               | Choose a password a put it in the clipboard                        |
| pass     | otp                    | Generate a totp token and put it in the clipboard                  |
|          |                        |                                                                    |  
| docker   | container_attach       | Choose a runing container and attach to it                         |
| docker   | container_stop         | Choose a running container and stop it                             | 
| docker   | container_start        | Choose a stopped container and starts it                           | 
| docker   | container_get_shell    | Choose a running container and starts a shell                      | 
| docker   | container_inspect      | Choose a running container and run's docker inspect on it          | 
| docker   | container_ip           | Choose a running container and get it's IPAddress                  | 
| docker   | container_metrics      | Choose a running container and get the app metrics                 | 
| docker   | containers_del_stopped | Choose a running container and get the app metrics                 | 
|          |                        |                                                                    |
| ble      | connect                | Choose a bluetooth paired device and connect to it                 | 
| ble      | disconnect             | Disconnects from the currently connected device                    | 
|          |                        |                                                                    |
| systemd  | service_stop           | Choose a running service and stop it                               | 
| systemd  | service_start          | Choose a stopped service and start it                              | 
| systemd  | service_status         | Choose a service and get it status it                              | 
| systemd  | service_cat            | Choose a service and get it's configuration file                   | 
| systemd  | service_disable        | Choose an enabled service and disable it                           | 
| systemd  | service_enable         | Choose a disabled service and enable it                            | 
|          |                        |                                                                    |
| circleci | launch_job             | Choose a job from your ci configuration and run it locally         |
| circleci | check_configuration    | validate your circleci configuration                               |
|          |                        |                                                                    |
| apt      | remove_and_clean       | Run's apt autoclean and autoremove                                 |
| apt      | upgrade                | Run's apt upgrade                                                  |
| apt      | upgrade_package        | Choose an upgradable package and upgrade it                        |
| apt      | binary_from_package    | Choose a binary from your path and see from which package it comes |
| apt      | conf_from_package      | Choose a file from /etc  and see from which package it comes       |

## required tools: 

* [ripgrep](https://github.com/BurntSushi/ripgrep)
* [enquirer](https://github.com/enquirer/enquirer)
* [jq](https://stedolan.github.io/jq/)
* [yq](https://kislyuk.github.io/yq/)
* [curl](https://curl.se/)
* [gnu awk](https://www.gnu.org/software/gawk/)
* [circleci cli](https://circleci.com/docs/2.0/local-cli/)
* [github cli](https://github.com/cli/cli)
* [docker](https://www.docker.com/)
* [git](https://git-scm.com/)
* [apt-file](https://wiki.debian.org/apt-file)
* [pass](https://www.passwordstore.org/)
* [pass-otp](https://github.com/tadfisher/pass-otp)
