# tunnel-plugin-index

This repository is the centralized plugin index for [Tunnel][tunnel-site], inspired by [krew-index][krew-index]. It is meant to be useful only for plugin developers.

- **If you are a Tunnel user:** You can find the list of Tunnel plugins at the
  [Tunnel plugin website][tunnel-plugin-site].

- **If you are a Tunnel plugin developer:** Read the [Developer Guide][dev-guide] to learn how to package and publish a plugin in this repository.


## Submitting new plugins

To learn how to create a new plugin and submit it to `tunnel-plugin-index`, read the [Developer Guide][dev-guide] and make a pull request to this repository.

The decision criteria for plugins accepted to the centralized repository are evaluated on a case-by-case basis as the community arrives to a decision on the admission criteria for this repository.

If your plugin is rejected from this repository, you can host your own repository to distribute your plugin with Tunnel.

## Community

### Bug reports

- If you're having an issue with an installed **plugin itself**, file an issue for the repository the plugin's source code is hosted at.
- If you're having a problem **installing or upgrading a plugin**, file an issue in this repository.
- If you have a problem with the **Tunnel itself**, please file an issue in the [Tunnel][tunnel-repo] repository.

[krew-index]: https://github.com/kubernetes-sigs/krew-index/
[tunnel-site]: https://khulnasoft.github.io/tunnel/latest/
[tunnel-repo]: https://github.com/khulnasoft/tunnel
[tunnel-plugin-site]: https://khulnasoft.github.io/tunnel-plugin-index/
[dev-guide]: https://khulnasoft.github.io/tunnel/latest/docs/plugin/developer-guide/
