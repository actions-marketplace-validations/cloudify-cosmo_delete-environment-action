Deletes an environment by running the `uninstall` workflow and deleting the deployment. Optionally,
also deletes the blueprint from which the deployment was created.

# Prerequisites

## Environment Variables

This Action uses the Cloudify Profile environment variables described in the official
Cloudify documentation (see [More Information](#more-information) below).

# Inputs

(Certain commonly-used inputs are documented in our official website; see [More Information](#more-information) below)

Name | Description
-----|------------
`delete-blueprint` | If set to `true`, then the blueprint from which the deployment was created will also be deleted (if no more deployments of that blueprint exist)
`ignore-failure` | If set to `true`, then errors occuring during the `uninstall` execution are ignored

# More Information

Refer to [Cloudify CI/CD Integration](https://docs.cloudify.co/latest/working_with/integration/) for additional information about
Cloudify's integration with CI/CD tools.
