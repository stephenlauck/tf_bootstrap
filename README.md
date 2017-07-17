# Terraform Bootstrap

1. write some terraform
2. put into VCS
3. setup TFE SAAS


* get aws access from #team-support-eng
* save aws credentials `~/.aws/credentials`

```
[default]
aws_access_key_id = ACCESS_KEY
aws_secret_access_key = SECRET_KEY
```

```
brew install terraform
```

```
mkdir tfexample
emacs example.tf
terraform plan
terraform apply
terraform show
terraform destroy
```

```
git init
git add .
git commit
```
