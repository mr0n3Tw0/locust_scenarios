# locust_scenarios
Locust load test scenario

locustfile.py - scenario file, before start need to download locust, for sure use virtualenv!.

1. Create virtualnev environment - $ virtualenv env
   activate virualenv environment - $ source env/bin/activate

2. Download locust - $ pip install locust

3. Start scenario - $ locust 
   and open http://127.0.0.1
   take port from CLI when you start locust, exemple of CLI output: Starting web monitor at http://*:8089
