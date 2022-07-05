# k8s-lab-ejercicios
Ejercicios preparatorios Kubernetes


# Ayuda

Comandos útiles para usar en estos laboratorios

```shell
$ kubectl api-resources         # Lista de los tipos de recursos


$ kubectl explain <resource>    # Mostrar información acerca de los recursos
$ kubectl explain deployment


# Listar recursos dentro de un cluster
$ kubectl get <resource>                    # En el namespace actual
$ kubectl get <resource> -n <namespace>     # En un namespace específico
$ kubectl get <resource> --all-namespaces   # En todos los namespace
$ kubectl get <resource> -o wide            # Agregar información al recurso
$ kubectl get <resource> -o yaml            # Salida en formato YAML
$ kubectl get <resource> -o json            # Salida en formato JSON

# Ejemplo de ejecución
$ kubectl get pods [-n abc|--all-namespaces] [-o wide|yaml|json]

```

See: [kubectl - Cheat Sheet](https://kubernetes.io/docs/reference/kubectl/cheatsheet/)
for a more extended overview of the `kubectl` command.