# Troubleshooting

## Common Issues
### Issue: VMs are not provisioning
- **Cause**: Hyper-V is not enabled.
- **Solution**: Verify Hyper-V is enabled on the host machine.

### Issue: Bitbucket nodes are not syncing
- **Cause**: Network misconfiguration.
- **Solution**: Check the network settings and ensure all nodes can communicate.

### Issue: Pipeline fails on rerun
- **Cause**: Terraform state inconsistency.
- **Solution**: Check and resolve state conflicts in Terraform.