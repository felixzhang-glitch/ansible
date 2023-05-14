# ansible

```
#指定服务ip执行
ansible-playbook dodpPipelineWorker.yaml --extra-vars "service_action=restart" -l 10.62.6.86

#指定服务执行动作
ansible-playbook --extra-vars "service_action=status"
``` 
