web: grafana-server
postdeploy: wget https://grafana.com/api/plugins/goshposh-metaqueries-datasource/versions/0.0.3/download && unzip download -d /app/public/app/plugins && rm -rf download && service grafana-server restart
