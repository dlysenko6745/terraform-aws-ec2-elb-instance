# terraform-aws-ec2-elb-instance
```

module "terraform6_elb" {
  source = ""dlysenko6745/ec2-elb-instance/aws""
  instance_type = var.instance_type
  ami = var.ami
  key_name = "diana"
#   elb_name = "tuncay-terraform6-elb"
#   availability_zones = ["us-east-2a", "us-east-2b", "us-east-2c"]
}
```
