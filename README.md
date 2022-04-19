OPA Sample [![Hits](https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Fnumerica-ideas%2Fopa-sample&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)](https://blog.numericaideas.com)
==========

Sample OPA project for policies evaluations and bundles fetching using AWS Lambda function + S3.

Running
-------
Once ran the command `sh run.sh`, we can test the policy execution by opening the following URL in a browser: http://localhost:8181/v1/data/sample/authz

Bundle
------
Generating a bundle is simply done by running the comand `sh bundle.sh`, while it's also possible to run it using the generated bundle by hitting `sh run-bundle.sh`.

Management API
--------------
This small OPA project is runnable using the management API located at
[https://github.com/numerica-ideas/opa-management-api](https://github.com/numerica-ideas/opa-management-api)
