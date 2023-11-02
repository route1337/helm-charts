Public Helm Charts
==================
This repo contains the various Helm charts used by Route 1337 LLC that we have made publicly available for the Devops community.

Using our charts
----------------
Our charts are hosted via Cloudflare Pages at [https://helm-charts.route1337.com](https://helm-charts.route1337.com).  
We have a basic index page listing the name, description and latest version of the charts.

A note on dependencies
----------------------
Some of these charts might rely on external services. If that is the case we will note that in the `templates/NOTES.txt` file for that chart.  
We would use the `Chart.yaml` dependencies field however we're experimenting with how that's going to work out regarding automation.

pre-commit
----------
This repo uses Yelp's [pre-commit](https://pre-commit.com/) to manage some pre-commit hooks automatically.  
In order to use the hooks, make sure you have `pre-commit`, and `helm` in your `$PATH`.  

Donate To Support These Helm Charts
-----------------------------------
Route 1337 LLC's open source code heavily relies on donations. If you find these Helm charts useful, please consider using the GitHub Sponsors button to show your continued support.

Thank you for your support!
