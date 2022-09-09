# Jobs and Plugins Demo

This repositories contains sample jobs and plugin used to demonstrate how to create automated data pipeline:

1. Ingest data in XML format . We ingest currency rate of USD to Polish Zloty for last year from Polish Bank APIs (but could be any source)
2. Transform data using parameterized SQL only to create aggreate table 
3. Show how to deploy and operate the data job in production
4. Create plugins to affect all data jobs in transparent way to ensure stability and security.


This repo structure:
- Directory "jobs" contains a sample data job that can be implemented by data engineers.
- Directory "plugins" contains a plugin expected to be developed and once installed it will be automatically applied for all data jobs created by all data engineers in the company.
