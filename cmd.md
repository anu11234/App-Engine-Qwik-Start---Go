# App Engine: Qwik Start - Go || **GSP070**

**Command:**

```bash
git clone https://github.com/GoogleCloudPlatform/golang-samples.git && cd golang-samples/appengine/go11x/helloworld && sudo apt-get update && sudo apt-get install -y google-cloud-cli-app-engine-go && gcloud app create --region=$(gcloud config get-value compute/region 2>/dev/null || echo "us-central") && gcloud app deploy --quiet
