# Kestra Docs

Steps to Start Kestra:

1. Ensure Docker is installed and running on your machine.
2. Execute the following command in your terminal:

```bash
docker run --pull=always --rm -it -p 8080:8080 --user=root -v /var/run/docker.sock:/var/run/docker.sock -v /tmp:/tmp kestra/kestra:latest server local
```

3. Wait for Kestra to start. This may take a few minutes as it downloads the necessary images if they are not already present.
4. Once started, you can access the Kestra UI by navigating to `http://localhost:8080` in your web browser.

