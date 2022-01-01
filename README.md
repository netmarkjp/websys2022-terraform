# WEBSYS2022 Terraformサンプル

クラウドコンピューティングの講義で利用するTerraformサンプル

## 実行の前提条件

- Terraformがインストールされている
    - Terraform v1.1.2、 provider.aws v3.37.0 でテスト済み
    - https://learn.hashicorp.com/tutorials/terraform/install-cli

## 実行方法

```sh
terraform init
terraform plan
terraform apply

# 終わったら
terraform destroy
```
