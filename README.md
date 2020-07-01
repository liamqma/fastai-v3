# Starter for deploying [fast.ai](https://www.fast.ai) models on Google Cloud Run

The sample app described here is up at https://flower-classifier-7fqsgrmbxa-de.a.run.app/. Test it out with flower images!

You can test your changes locally by installing Docker and using the following command:

```
docker build -t fastai-v3 . && docker run --rm -it -p 8080:8080 fastai-v3
```