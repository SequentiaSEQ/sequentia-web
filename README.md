# Sequentia Web UI
Simple server-side rendered web page to connect to your Sequentia instance

# Usage

Run web server on port 8080

```bash
docker run -it --rm --name web -p 8080:8080 -e RPC_USER=sequentia -e RPC_PASS=sequentia -e RPC_HOST=localhost -e RPC_PORT=18884 -e REMOTE_RPC_HOST=tiero.com -e REMOTE_P2P_HOST=tiero-donde-stas.com  -e P2P_PORT=18886 ghcr.io/sequentiaseq/sequentia-web
```
