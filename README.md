github-workflows-builder
========================
```yaml
- uses: actions/upload-artifact@v4
  with:
    name: my-artifact
    include-hidden-files: true


- name: setup Java 11
  uses: actions/setup-java@v3
  with:
    distribution: 'temurin'
    java-version: '11'
```
