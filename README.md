# Xcode Staple

This Action staples notary service tickets to macOS products.

## Basic Usage

```yaml
- name: "Staple Release Build"
  uses: BoundfoxStudios/xcode-staple@v1
  with:
    product-path: "Export/Application.app"
```

## Full Example

The [BoundfoxStudios/community-project](https://github.com/BoundfoxStudios/community-project) project is an example Unity macOS project with a [notarization.yml](https://github.com/BoundfoxStudios/community-project/blob/develop/.github/workflows/notarization.yml) workflow that shows all the steps needed to go from creating a release in GitHub to ending up with a `.zip` file that contains a signed and notarized application.

## Related Actions

 * [Xcode Notarize](https://github.com/marketplace/actions/apple-xcode-notarize) - Notarize a macOS product.
 * [Xcode Staple](https://github.com/marketplace/actions/apple-xcode-staple) - Staple a Notarization Ticket to your product.
 * [Xcode Select](https://github.com/marketplace/actions/apple-xcode-select) - Select a Xcode version.

## License and Contributions

This Action is licensed under the [MIT](LICENSE) license. Contributions are very much welcome and encouraged but we would like to ask to file an issue before submitting pull requests. 
