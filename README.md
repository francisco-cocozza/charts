# charts
https://francisco-codefresh.github.com/charts

```
$ cd <dir of the repo of the chart>
$ helm package mychart
$ mv mychart-0.1.0.tgz docs
$ helm repo index docs --url https://francisco-codefresh.github.io/charts/
$ git add -i
$ git commit -av
$ git push origin main
```