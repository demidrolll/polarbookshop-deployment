#Deploy
k8s_yaml(['kubernetes/platform/development/services/postgresql.yml'])

#Manage
k8s_resource('polar-postgres', port_forwards=['5432'])
