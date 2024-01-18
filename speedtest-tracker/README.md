# SpeedTest-Tracker

Please configure the `dnsConfig` section of the pod specification according to your needs:

```yml
dnsPolicy: None
dnsConfig:
  nameservers:
    - 10.152.183.10
    - 8.8.8.8
  searches:
    - speedtest-tracker.svc.cluster.local
  options:
    - name: ndots
      value: "5"
```
