# ssm_executor

Example AWS SSM Script Executor.

Edit/Modify to suit your needs.

In this example rundeck servers have IAM roles attached to them.

ec2 discovery plugin used to populate nodes.

Usage :

$ zip -r ssm_executor-plugin-1.0.0.zip ssm_executor-plugin-1.0.0/

$ cp ssm_executor-plugin-1.0.0.zip /var/lib/rundeck/libext/

$ /etc/init.d/rundeckd restart


Will show up as "SSM Script Plugin" under the Default Node Executor for a Project.

Enjoy