## NASA-MarsApiTest


### How to Import?

Import the [collection (.json) file](https://github.com/vinicius-candido/NASA-MarsApiTest/blob/main/NASA.postman_collection.json) on Postman. Go to File > Import and select the file. The same action can be done at Collections page, as shown below.

![imagem_2022-09-07_123922592](https://user-images.githubusercontent.com/15057071/188920386-7a7c2dd8-4577-4e6b-a0b6-ab8fcdead2e7.png)


### How to Run?

Important: I stored NASA API key as an environment secret variable  {{NASA-Token}}, this must be created and the value updated after importing the collection.

At Collections tab, click the NASA collection option and 'Run collection'

![imagem_2022-09-07_124056811](https://user-images.githubusercontent.com/15057071/188920726-df8a67a0-f836-436b-8850-49c7211ed537.png)


### Where is the code?

All tests and scripts to support it are at 'Tests' tab.

![imagem_2022-09-07_125424238](https://user-images.githubusercontent.com/15057071/188923804-5c1ede02-ec74-4c81-b728-13872cd7c7e3.png)


### Results 

It is expected that the last validation fails, because the amount of Curiosity photos is greater than 10x the amount of other cameras photos at 1000 Martian sol.

![Postman_bC44ESzpvj](https://user-images.githubusercontent.com/15057071/188919306-25147652-5847-4f6f-b400-d94318cc1182.png)
