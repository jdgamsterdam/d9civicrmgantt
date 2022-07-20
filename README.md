One thing that has annoyed me for years is the lack of a working Gantt Module or CiviCRM Extension. 
Due to the many ways people use Drupal and CiviCRM, I created an “Instruction Guide” (With Code Samples) rather than a module or extension.  

I found the Gantt chart in Google Charts works very well.  Unfortunately, none of the normal Drupal Charts modules support the Gantt Chart. So, I built a very simple Javascript interface.  There are lots of other Gantt Libraries out there, but Google Should be pretty safe. 

While this solution is built for a CiviCRM it uses standard JSON as a data source, so it could really be repurposed for any CRM or other system where a JSON Dataset is available (e.g., you could store task activities as Drupal Nodes and then create a View on the Node fields).

Within CiviCRM, I chose to use “standard” Activities with a few extra custom fields.  You could probably implement this system with events as well, but Activities seemed closer to the goals. But, there are some “gotchas” discussed in the documentation.

