# PA-nmon_light, Indexers Addon for Nmon Performance Monitor - Splunk Enterprise

Copyright 2014-2018 Guilhem Marchand

Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at

http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

See:

https://github.com/guilhemmarchand/nmon-for-splunk

https://splunkbase.splunk.com/app/1753

Purpose:

Light indexer package for the Nmon application for Splunk.
This package is designed to be deployed on the indexer layer, and eventually any Intermediate Heavy Forwarder. (Intermediate Universal Forwarder being recommended for intermediate layer!)
Purpose is providing the required configuration for indexing time parsing operations.

The deployment is required only if no deployment of the TA-nmon will be achieved on the first indexing time parsing layer. (where the data gets cooked)

Please consult the on-line documentation: http://nmon-for-splunk.readthedocs.io
