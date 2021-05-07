## Ruby

These settings apply only when `--ruby` is specified on the command line.

```yaml
package-name: azure_mgmt_confidentialledger
package-version: 0.1-preview
azure-arm: true
```

### Tag: package-0.1-preview and ruby

These settings apply only when `--tag=package-0.1-preview --ruby` is specified on the command line.
Please also specify `--ruby-sdks-folder=<path to the root directory of your azure-sdk-for-ruby clone>`.

```yaml $(tag) == 'package-0.1-preview' && $(ruby)
namespace: Microsoft.ConfidentialLedger
output-folder: $(ruby-sdks-folder)/confidentialledger
```