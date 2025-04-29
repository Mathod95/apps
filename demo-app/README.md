# demo-app
### Installation:
To install this application using the `argocd-autopilot`, assuming you already have gone through the [bootstrap process](https://argocd-autopilot.readthedocs.io/en/latest/Getting-Started/), run the following:
```bash
argocd-autopilot app create hello-world --app github.com/Mathod95/apps/demo-app/ -p management
argocd-autopilot app create hello-world --app github.com/Mathod95/apps/demo-app/ -p staging
argocd-autopilot app create hello-world --app github.com/Mathod95/apps/demo-app/ -p production
```