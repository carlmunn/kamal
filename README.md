# Kamal: Deploy web apps anywhere

~~Forked to add builder.options which allows "--ssh $SSH_AUTH_SOCK" to be given to the builder. This is required when pulling code from repos that need ssh keys. The options could be anything, I've made it agnotic.~~

The repo this was forked from now supports this feature. This repo will disappear eventually.

From bare metal to cloud VMs, deploy web apps anywhere with zero downtime. Kamal has the dynamic reverse-proxy Traefik hold requests while a new app container is started and the old one is stopped. Works seamlessly across multiple hosts, using SSHKit to execute commands. Originally built for Rails apps, Kamal will work with any type of web app that can be containerized with Docker.

➡️ See [kamal-deploy.org](https://kamal-deploy.org) for documentation on [installation](https://kamal-deploy.org/docs/installation), [configuration](https://kamal-deploy.org/docs/configuration), and [commands](https://kamal-deploy.org/docs/commands).

## Contributing to the documentation

Please help us improve Kamal's documentation on the [the basecamp/kamal-site repository](https://github.com/basecamp/kamal-site).

## License

Kamal is released under the [MIT License](https://opensource.org/licenses/MIT).
