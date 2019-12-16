# MikrOps Datasets
Some datasets used by MikrOps project

----

# Export

## app_device
```
./manage.py dumpdata app_device.DeviceType > app_device.DeviceType.json
./manage.py dumpdata app_device.Vendor > app_device.Vendor.json
./manage.py dumpdata app_device.OrganizationVendor > app_device.OrganizationVendor.json
./manage.py dumpdata app_device.Model > app_device.Model.json
```

## app_job
```
./manage.py dumpdata app_job.Job > app_job.Job.json
./manage.py dumpdata app_job.JobVariable > app_job.JobVariable.json
./manage.py dumpdata app_job.JobAction > app_job.JobAction.json
./manage.py dumpdata app_job.JobActionParameter > app_job.JobActionParameter.json
./manage.py dumpdata app_job.JobTask > app_job.JobTask.json
./manage.py dumpdata app_job.JobTaskParameter > app_job.JobTaskParameter.json
```

----

# Import

## app_device
```
./manage.py loaddata --app app_device app_device.DeviceType.json
./manage.py loaddata --app app_device app_device.Vendor.json
./manage.py loaddata --app app_device app_device.OrganizationVendor.json
./manage.py loaddata --app app_device app_device.Model.json
```

## app_job
```
./manage.py loaddata --app app_job app_job.Job.json
./manage.py loaddata --app app_job app_job.JobVariable.json
./manage.py loaddata --app app_job app_job.JobAction.json
./manage.py loaddata --app app_job app_job.JobActionParameter.json
./manage.py loaddata --app app_job app_job.JobTask.json
./manage.py loaddata --app app_job app_job.JobTaskParameter.json
```
