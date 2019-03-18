## Release History

### Version next

* Convert computed metrics to new format
* Adjusted build to use metricly-cli for validation

### Version 1.8.0

* Add computed metrics for index operations per second.

### Version 1.7.0

* Remove policy for Elevated CPU Activity
* Remove policy for Elevated Processing Time
* Remove policy for Elevated JVM Threads

### Version 1.6.0

* Add policy for Cluster Health Degraded to Red
* Add policy for Cluster Health Degraded to Yellow
* Add policy for Disk space is more than 75% used on data node
* Add policy for Elevated Fetch Time
* Add policy for Elevated Flush Time
* Add policy for Elevated Indexing Time
* Update Elevated JVM Heap Percent Usage policy to require >80% and both deviations

### Version 1.5.1

* Fix policy elementTypes compatibility

### Version 1.5.0

* Add computed metrics for average Elasticsearch query times
* Update query time dashboard widgets to use the new computed metrics

### Version 1.4.1

* Readme formatting

### Version 1.4.0

* Replaced existing summary dashboard with 4 summary dashboards
* Added 3 policies

### Version 1.3.0

* Updated gridstack dashboard layouts

### Version 1.2.3

* Updated package compatibilities.

### Version 1.2.2

* Updated configurations for narrower, more accurate, scope.

### Version 1.2.1

* Fixed a bug where some metrics weren't getting units applied.

### Version 1.2.0

* Added summary dashboard and metric units.

### Version 1.1.0

* Renamed computed metrics to follow new naming convention (netuitive.linux.* versus netuitive.diamond.*)

### Version 1.0.2

* Fixed a bug in the ACE configuration that prevented the package from being provisioned.

### Version 1.0.1

* Turned off correlation for some metrics to allow for more efficient processing.

### Version 1.0.0

* Initial production release of the package for monitoring ElasticSearch resources.  This package works with the ElasticSearch collector of the Linux Agent.
