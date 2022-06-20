# Postman API Network

This collection is now available in [our workspace](https://www.postman.com/zuva-ai/workspace/zuva-api-v2/overview) on the Postman API Network.

# Zuva DocAI's Postman Collections

This repository contains a v2.1 Postman Collection for all of Zuva DocAI's endpoints.

# Pre-requisites

* [Postman](https://www.postman.com/downloads/)
* [A Zuva DocAI Account](https://zuva.ai/docai/#form)

# Postman Environment

You will need to create an Environment in your Postman.

This environment should contain the following keys:

* zdai-base-url : This is where your ZDAI Base URL goes (e.g. https://<url_to_instance>/api/v2)
* token : Token goes here (without "Bearer" prepended)

# Run Collection

To run most requests in a sensible order, you can use the the [Run Collection](https://learning.postman.com/docs/running-collections/intro-to-collection-runs/). The tests for each endpoint have been configured to
correctly poll and/or trigger the appropriate next request, stepping through file upload, OCR, field extraction, document
classification and language classification. Training-related requests are currently excluded from the run.


# Documents

This repository contains a publicly-available document found at the following:

https://www.sec.gov/Archives/edgar/data/1690511/000119312517376090/d486317dex1010.htm

To use these files in the Collection, move them to your Postman Files working directory (~/Postman/files).

