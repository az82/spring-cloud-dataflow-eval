# Spring Cloud Dataflow Evaluation

* [Spring Cloud Dataflow Helm Deployment](https://dataflow.spring.io/docs/installation/kubernetes/helm/)

    ```bash
    helm repo add my-repo https://charts.bitnami.com/bitnami
    helm install my-release my-repo/spring-cloud-dataflow
    ```

    * Achtung: Läuft nicht mit neueren K8s Versionen, das Dashboard benutzt eine nicht unterstützte Kubernetes API.
    * Kubernetes v1.19 nutzen.

* [Spring Cloud Dataflow Shell](https://www.springcloud.io/post/2022-04/spring-cloud-dataflow-shell/#gsc.tab=0)
    * Installation:

      ```bash
      wget https://repo.spring.io/snapshot/org/springframework/cloud/spring-cloud-dataflow-shell/2.10.2-SNAPSHOT/spring-cloud-dataflow-shell-2.10.2-SNAPSHOT.jar
      ```

* [Spring Cloud Dataflow Getting Started with Task Processing](https://dataflow.spring.io/docs/batch-developer-guides/getting-started/task/)
    * Beachte [Stackoverflow #41000552](https://stackoverflow.com/questions/41000552/spring-cloud-data-flow-task-cant-start-on-kubernetes-cluster)

* [Batch Processing with Spring Batch](https://dataflow.spring.io/docs/batch-developer-guides/batch/spring-batch/)

* [REST API Guide](https://docs.spring.io/spring-cloud-dataflow/docs/current/reference/htmlsingle/#api-guide)