# Files Important

- readonly
- Dockerfile


# How run in docker playground

P=\`base64 -d readonly\` && docker run --env PRIVATE_KEY="$P" --env PORT=9999 -p 9999:9999 cfg-server