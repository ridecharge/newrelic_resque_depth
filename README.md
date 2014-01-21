newrelic_resque_depth
=====================

A newrelic plugin for monitoring resque, including the number of pending 
items per queue in each namespace.

The newrelic_resque_depth plugin can be configured for multiple resque 
servers with multiple namespaces. The summary page shows stats on 
Pending, Processing Rate, and Failed jobs. The Overview provides a 
Queue Depth chart, which shows pending records for each queue in the 
namespace; a Queue Processing chart, which provides processed, pending, 
and failed jobs; and a Workers and Queues chart, which provides number 
of queues, workers, and working workers.

Installing and Running the resque depth agent
---------------------------------------------
1. Go to the [tags list](https://github.com/ridecharge/newrelic_resque_depth/tags) and find the latest tar.gz
2. Download and extract the source
3. Run `bundle install` to install the required gems
4. Copy `config/template_newrelic_plugin.yml` to `config/newrelic_plugin.yml`
5. Replace "YOUR LICENSE_KEY_HERE" with your New Relic license key
6. Add your redis URI(s) and namespace(s) information to the configuration
7. Execute ./newrelic_resque_depth_plugin
8. Open your New Relic account in the browser and look for ResqueDepth in
the left-hand pane. 

Issues and Support
------------------
Please use [Github issues](https://github.com/ridecharge/newrelic_resque_depth/issues) for all support requests.
