# Terraform_module_learning
custom terraform module

```
# terraform init
# terraform apply -auto-approve

output:

Changes to Outputs:
  + taco = {
      + cheese = "jack"
      + meat   = "chicken"
      + salsa  = "tomatillo"
      + shell  = "corn"
    }

```
or
```
# terraform apply -auto-approve -var meat=beef -var cheese=blanco

Outputs:

taco = {
  "cheese" = "blanco"
  "meat" = "beef"
  "salsa" = "picante"
  "shell" = "corn"
}
```