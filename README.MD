# For local use (without container):

### install: 

```pip install fastapi uvicorn pydantic```

### run:

```uvicorn main:app --reload```

# For container use:

### load container:

```docker podman load -i myproject-full.tar.gz```

### Launch the container:

```docker run -d -p 8000:8000 --name url-shortener url-shortener```