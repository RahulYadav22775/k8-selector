3Selectors

Taint the node
---

kubectl taint nodes ip-192-168-14-185.ec2.internal    hardware=gpu:NoSchedule
---

label node
---

kubectl label nodes ip-192-168-14-185.ec2.internal  hardware=gpu
---