# rpi-certbot-node
[deprecated]

Docker image with Certbot and Nodejs for arm32v7 (Raspberry Pi)

Example:
```bash
docker run -d \
  -v /path/to/app/dir:/app \
  -e CERT_DOMAIN=your.domain.co \
  -e CERT_EMAIL=your_email@gmail.com \
  -e APP_ENTRY=index.mjs \
  -p 80:80 \
  -p 443:443 \
  --name app \
  kacao/rpi-certbot-node
```
