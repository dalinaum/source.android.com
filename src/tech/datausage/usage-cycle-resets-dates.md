<!--
   Copyright 2012 The Android Open Source Project

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.
-->

Users can specify a day of month upon which their data usage
resets. Internally, cycle boundaries are defined to end at midnight
`(00:00) UTC` on the requested day. When a month is shorter than the
requested day, the cycle resets on the first day of the subsequent
month. For example, a cycle reset day of the 30th would cause a reset
on January 30 at `00:00 UTC` and March 1 at `00:00 UTC`.
