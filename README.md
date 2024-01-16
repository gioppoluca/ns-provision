To create the python project from openapi:

```
pip install datamodel_code_generator==0.11.19
pip install fastapi-code-generator
fastapi-codegen --input ./ns-provision-openapi.yml --output app
sudo apt install uvicorn
cd app
uvicorn main:app --reload
```

