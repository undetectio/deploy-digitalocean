# DigitalOcean Undetect Deployment

This repo allows a 1-click deployment of a [Stealthium](https://undetect.io/solutions/) cluster to DigitalOcean. To start, simply click the button below:

[![Deploy to DO](https://www.deploytodo.com/do-btn-blue.svg)](https://cloud.digitalocean.com/apps/new?repo=https://github.com/undetectio/deploy-digitalocean/tree/main)

Make the following changes:

* Select `Edit Plan` and change the resource to 1x the `Pro` plan or higher
* Select `Environment Varables` -> `Edit` and change the value of `UNDETECT_KEY_LOWERCASE` to your Undetect key lowercased (see [the docs](https://docs.undetect.io/integration/cloud?id=digitalocean)). Click `Save`.

That's it - go to the final step and click `Create Resources`. Your cluster will be up and running in a minute.
