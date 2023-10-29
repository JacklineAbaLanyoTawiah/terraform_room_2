# terraform_room_2

[Friday 11:35] Caleb Yeboah
The terraform plan can be used without passing a variable. Terraform would use the default variable in this case

To pass a different variable name, use: terrafom plan -var "instance_name=room_one_instance"

Same with terraform apply, use: terrafom apply -var "instance_name=room_one_instance"
