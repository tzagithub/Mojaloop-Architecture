# Kubernetes Basics – Deploy and Verify Service Connectivity

---

## Goal

Gain hands-on experience with Kubernetes by:
- Deploying a simple nginx application
- Exposing it using a Kubernetes Service
- Verifying internal cluster connectivity
- Understanding basic Kubernetes networking concepts

---

## Scope

This lab covers:
- Deployment of nginx application
- Exposure using ClusterIP Service
- Internal connectivity testing using a temporary pod
- Inspection of Kubernetes resources (Pods, Services, Endpoints)
- Understanding traffic flow inside Kubernetes cluster

---

# 1. Deploy Application

A Deployment is created using the nginx image.

