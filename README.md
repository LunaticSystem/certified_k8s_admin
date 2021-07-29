# CKA (Certified Kubernetes Administrator) Cert Notes

[CKA Udemy Course](https://www.udemy.com/course/certified-kubernetes-administrator-with-practice-tests)


### Course Outline:

- Section 1: Introduction
- Section 2: Core Concepts
- Section 3: Scheduling
- Section 4: Logging & Monitoring
- Section 5: Application Lifecycle Managment
- Section 6: Cluster Maintenance
- Section 7: Security
- Section 8: Storage
- Section 9: Networking
- Section 10: Desing and Install a K8s Cluster
- Section 11: Install "Kubernetes the kubeadm way"
- Section 12: End to End tests on k8s
- Section 13: Troubleshooting
- Section 14: Other Topics
- Section 15: Lightning Labs
- Section 16: Mock Exams
- Section 17: Course Conclusion


### Notes:

### Useful Commands:

Check DNS from an Ephemeral BusyBox pod:

```bash
$ kubectl run -it --rm --restart=Never busybox --image=busybox:1.28 -- nslookup <dns-hostname>
```

Get service information:

```bash

```
