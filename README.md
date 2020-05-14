# nginx-accel
Build script for a high performance, optimized image NGINX for use with Redis and PHP-FMP. Deliver sites and applications with performance, reliability, security, and scale. This NGINX server offers advanced performance, web and mobile acceleration, security controls, application monitoring, and management. Inspried by https://github.com/openbridge/nginx

![Image of Nginx](https://cdn.openbridge.com/assets/images/openbridge-nginx-small.png)

# NGINX Accelerated including Reverse Proxy, Redis, CDN, Lets Encrypt and much more!

Forked from [openbridge/nginx](https://github.com/openbridge/nginx) for Docker. Combined with PHP-FPM from [high performance PHP-FPM](https://github.com/openbridge/ob_php-fpm)

Currently supported: Debian/Ubuntu

## Features

The image includes configuration enhancements for;
* Reverse Proxy
* SEO optimizations
* Customizable configurations
* SSL with support for Lets Encrypt SSL certificates
* Mime-type based caching
* Redis LRU cache
* Fastcgi cache
* Proxy cache
* tmpfs file cache
* Brotli and Gzip compression
* Redirects for moved content
* [Security & Bot Protection](https://github.com/mitchellkrogza/nginx-ultimate-bad-bot-blocker)
* Monitoring processes, ports, permissions... with Monit
* Standardized UID/GID and Permissions (www-data)
* Support GeoIP
* Rate limited connections to slow down attackers
* CDN support
* Cache purge

There are many, many other benefits to this system. Give it a try!

# AUTH
- I'm currently tried my best to fork the script. This script is not really at it best form because of my limitation working with bash script and commands, but at least it working as I expected. So, I need some help to refactor this script for better working.

# TODO
- [ ] Add PageSpeed module

# Issues

If you have any problems with or questions about this script, please create new GitHub issue.

# Contributing

You are invited to contribute new features, fixes, or updates, large or small. I'm always thrilled to receive pull requests, and do my best to process them as fast as we can.

# License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details
