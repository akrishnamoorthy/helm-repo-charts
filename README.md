# helm-repo-charts
This is a personal chart repository for building Reusable helm charts for projects under Github account (akrishnamoorthy)
This repository contains [Helm](https://helm.sh) charts for various projects

* [search](charts/app1/) - This is a sample boot strap application which is build on SOLR (Lucene based search index)

## Installing Charts from this Repository

Add the Repository to Helm:

    helm repo add my-helm-charts https://akrishnamoorthy.github.io/helm-repo-charts/

Install search:

    helm install my-helm-charts/search

