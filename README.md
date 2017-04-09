# README.md
A simple playbook that loads security groups in a yaml file into AWS for a given
region and vpc

```
ansible-playbook aws_sg_loader.yaml -e"region=us-west-2 vpc_id=vpc-71f8dc77 var_file=demo.yml
```

