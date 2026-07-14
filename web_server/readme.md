# Web Server

This project covers the basics of configuring a web server using **Nginx** and deploying files to a remote server.

## Learning Objectives

- Understand the role of a web server.
- Understand the basics of DNS.
- Transfer files securely using `scp`.
- Install and configure Nginx.
- Configure HTTP redirections.
- Create a custom 404 error page.
- Design a custom HTML 404 page.

## Project Structure

```
web_server/
├── 0-transfer_file
├── 1-install_nginx_web_server
├── 2-setup_a_domain_name
├── 3-redirection
├── 4-not_found_page_404
├── 5-design_a_beautiful_404_page.html
└── README.md
```

## Files

| File | Description |
|------|-------------|
| `0-transfer_file` | Bash script to transfer a file to a remote server using `scp`. |
| `1-install_nginx_web_server` | Installs and configures Nginx to serve a web page containing "Holberton School for the win!". |
| `2-setup_a_domain_name` | Contains the configured `.tech` domain name. |
| `3-redirection` | Configures Nginx to redirect `/redirect_me` with an HTTP 301 status code. |
| `4-not_found_page_404` | Configures a custom 404 page containing "Ceci n'est pas une page". |
| `5-design_a_beautiful_404_page.html` | A creative HTML page used as the custom 404 page. |

## Requirements

- Ubuntu 20.04 LTS
- Bash
- OpenSSH
- Nginx

## Author

ALU System Engineering & DevOps
