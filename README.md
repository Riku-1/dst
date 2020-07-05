### Docker
from https://github.com/fairplay-zone/docker-dontstarvetogether


### CFn Template
```
aws cloudformation create-stack --stack-name dst --template-body file://./template.yml --capabilities CAPABILITY_IA
```

You have to set ssm parameters required in template.yml