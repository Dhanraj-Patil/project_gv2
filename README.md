# project_gv2
I created an microservice that reads from the rabbitmq queue created in project-gv (PART - 1) and uses Google Vision API to validate images in a Google Cloud storage bucket.

If an image is found to be explicit, delete it from the bucket while publishing appropriate events back on the queue

Dependencies: Erlang, Google Cloud Accout, Google Cloud Service Account, Vison API enbled in Google Cloud Console, Authentication Key, set Environment Variable GOOGLE_APPLICATION_CREDENTIALS= path to authentication key.

This is in continuation of project-gv.
