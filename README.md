# votingapp_kubernetes_solved

This is based on the original [example-voting-app](https://github.com/dockersamples/example-voting-app) repository from the [docker-examples](https://github.com/dockersamples) GitHub page

and modified it to work on the Kubernetes cluster.

Basically it's a solution of Kodekloud [voting-app kubernetes lab](https://kodekloud.com/courses/labs-kubernetes-crash-course/?context=youtube-ads-kubcrashcourse&utm_source=youtube&utm_medium=labs&utm_campaign=kubernetes_crash_course). And  thanks to Kodekloud for amazing lab.

![Kodekloud_kubernetes_lab_solved](https://github.com/nightfury000/votingapp_kubernetes_solved/blob/main/Kodekloud_kubernetes_lab_solved.png)
         (not visible labels(redis-service redis-deployment) :).
It took good amount of tries to work so I thought to upload the solution but do give it a try before going to solution.
<details open>
<summary>Steps</summary>
<br>
git clone https://github.com/nightfury000/votingapp_kubernetes_solved.git . While creating deployments and services do it one by one like first voting-app-deploy then voting-app-service in that way.
Most probable problem is service endpoint one, that occurred to me many times, in that case check the selector labels in deployment they should match to labels in services.
</details>
