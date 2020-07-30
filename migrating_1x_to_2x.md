# Migrating from version 1.x to version 2.0

If you plan to migrate from the technology preview version of {product-name-short} (1.x) to the generally available version (2.0), you must uninstall version 1.0 and then install version 2.0 as a clean installation. Upgrading directly from the product technology preview version 1.x of {product-title} to version 2.0 is not supported.

## Complete the following steps to migrate from version 1.x to version 2.0:

1. Detach each of your managed clusters from your {product-title-short} hub cluster before uninstalling the version 1.x. See Removing a cluster from management for instructions that explain how to remove the managed clusters.

2. Uninstall {product-title-short} version 1.x by completing the procedure in Uninstalling.

3. Install {product-title-short} version 2.0 by completing the procedure in Installing while connected online.

   * When you install version 2.0, you can enable automatic upgrades for future versions within the same major release by selecting the autormatic upgrade setting. If you prefer to run manual updates, you can select manual upgrade.

   * Automatic upgrade. If you select Automatic upgrades when you install the Red Hat Advanced Cluster Management operator, the Operator Lifecycle Manager automatically upgrades the version when a compatible upgrade is available. This method ensures that you always have the latest version of the operator with the latest fixes.

   * Manual upgrade. If you select Manual upgrades when you install the Red Hat Advanced Cluster Management operator, the cluster administrator determines when an upgrade occurs. When a compatible upgrade is available, the Operator Lifecycle Manager creates a request to upgrade. Someone with cluster administrator access must approve the request to upgrade to the new version.

4. Import the previously detached cluster into the version 2.0 hub cluster by completing the procedure in Importing a target managed cluster to the hub cluster.

