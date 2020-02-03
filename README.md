doc_mod Application

Build Command:
```
cd mta_doc_mod ; mkdir -p target ; mbt build -p=cf -t=target --mtar=mta_doc_mod.mtar
```

Deploy Command:
```
cf deploy target/mta_doc_mod.mtar -f
```

UnDeploy Command:
```
cf undeploy doc_mod -f --delete-services
```
