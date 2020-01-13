
# Sample Kubernetes Daemonset YAML for Halo Agent

## Configuration

Change the value for **AGENT_KEY** to match the agent key you retrieved from the CloudPassage portal or API/SDK.

If necessary for troubleshooting, add *“--debug”* as an additional line after *“—grid…”* in the container’s args section.


## Deployment

To deploy the Halo Daemonset:

 1. Download the halo-k8s-daemonset.yaml file 
 2. Replace the sample **AGENT_KEY** with the appropriate value for your Halo configuration
 3. Apply the daemonset by executing *kubectl -f halo-k8s-daemonset.yaml* against your Kubernetes cluster.
    
    

