# Cleanup

```bash
# If GKE
gcloud container clusters delete $NAME --region $REGION --quiet

# If AKS
# TODO: Delete LB

# If AKS
eksctl delete cluster -n $NAME
```