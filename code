provider "aws" {
  region  = "us-east-1"
}

resource "aws_instance" "app_server" {
  ami           = "ami-0d94353f7bad10668" 
  instance_type = "t2.micro"

  tags = {
    Name = "TestEC2Instance"
  }
}
