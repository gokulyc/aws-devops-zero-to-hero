

```bash
    # useful for E2E aws lambda
    
    # Dev useful for vscode local development
    pip install 'boto3-stubs[essential]' 'boto3[crt]' 
    # Prod 
    # requirements.txt not required for current usecase
    pip install -r requirements.txt -t .

```
