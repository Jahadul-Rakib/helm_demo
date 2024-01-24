1. `helm create <name_of_helm_chart>`
2. remove `appVersion` from Chart.yaml file.
3. `helm package <helm_directory>/ -d <chart-directory>`