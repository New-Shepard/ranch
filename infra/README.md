# Ground rules
1. Consider 'ap-northeast-2' as the first region for shepard project.
    > Because most of our potential customers reside in Korea.

2. AWS CDK is the first option for the IaC in this project
    > CDK reference : [aws-cdk github](https://github.com/aws/aws-cdk#getting-started)

3. Folder structure will be devided as followed by service coverage characteristics of AWS resources.   
    > (e.g. AZ base / Regional base / Global service)

4. We use python as the default language on CDK. And when we use python virtual env, use `.venv` or `.env` as the path of the virtual env. Otherwise, the path should be added to the `.gitignore` file properly.
