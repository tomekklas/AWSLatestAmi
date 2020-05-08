# AWSLatestAmi
this lambda functions retrieves latest ami for Ubuntu on weekly basis and places it in SecretStore ready to be used in CloudForamtion templates

to be used like this:
[['{{resolve:secretsmanager:SecretStoreName:SecretString:LatestAmiId}}' ]]
