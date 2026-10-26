# Week 1 Reflection – NGINX Pod and Deployment

This week, I worked through the Kubernetes fundamentals lab where I deployed a basic NGINX web server using both a Pod and a Deployment. I also learned about security contexts and how to scale workloads.

---

## ✅ What I Learned

- Pods are single units; deployments manage replicas and rollout strategies 
- Security Contexts improve workload isolation
- 
- 


---

## ❓ What Was Challenging

- Understanding why the Pod didn't start when missing the image tag
- the difference between ```kubectl get pod``` and ```kubectl get deployment```
- 

---

## 🧪 Commands I Practiced

```bash
kubectl apply -f nginx-pod.yaml

kubectl apply -f nginx-deployment.yaml

kubectl get pods

kubectl describe deployment nginx-deployment

kubectl scale deployment nginx-deployment --replicas=3

```

---

## 🔐 Security Improvements I Made

- Set ```runASNonRoot``` and disabled privilege escalation
- 

---

## 📝 Questions I Still Have

- 
- 
- 

---

## 📎 Related YAMLs

- `nginx-pod.yaml`
- `nginx-deployment.yaml`

---

## 🚀 Looking Ahead

I’m excited to explore GitOps in Week 2 and automate deployments using FluxCD.

