# API First Using Code Generator

```bash
  export PATH=$PATH:$JAVA_HOME/bin
  npm install @openapitools/openapi-generator-cli -g
  npx @openapitools/openapi-generator-cli generate -i doc/api.yaml -g	python-fastapi -o ./services/external-api
```

```bash
  python -m venv .env && source .env/Scripts/activate
  python -m pip install --upgrade pip
  # substituted uloop for winloop in Windows environment
  pip install -r requirements.txt

uvicorn src.openapi_server.main:app --port 7070 --reload
PYTHONPATH=src uvicorn openapi_server.main:app --host 0.0.0.0 --port 7070

```

## [Valid Test GUUID](https://guidgenerator.com/)

- d9896b61-f3f5-4838-b40c-307cfd71f02c
- afbb3f23-1e14-4ed7-a99a-34b90e5dd219
- a2f78610-030e-4b9e-b3fa-3aa574e7f9b1
- c41eb48f-492a-4a11-9cf8-62fa01157c0c
- 73b0d570-c356-43c5-9697-6897046bbc9a
