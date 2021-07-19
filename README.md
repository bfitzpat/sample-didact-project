# sample-didact-project

Simple project for use in a DevSandbox devfile.

Devfile might look like:

```
apiVersion: 1.0.0
metadata:
  name: didact-starter
projects:
  - name: sample-didact-project
    source:
      location: 'https://github.com/bfitzpat/sample-didact-project'
      type: git
components:
  - id: redhat/vscode-didact/latest
    type: chePlugin
    registryUrl: 'https://eclipse-che.github.io/che-plugin-registry/main/v3/'
    alias: didact-plugin
```
