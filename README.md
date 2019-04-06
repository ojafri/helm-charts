`git clone https://github.com/ojafri/helm-charts.git`

`cd helm-charts`

make changes to chart files as needed

`helm package charts/kafdrop`

`helm repo index ./ --url https://ojafri.github.io/helm-charts/`

commit/push to git afterwards

