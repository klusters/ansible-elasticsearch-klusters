ansible-elasticsearch-klusters

## Usage
### Environment Variables

GOOGLE_APPLICATION_CREDENTIALS: GCP Service Account Key file (path)
GCP_SERVICE_ACCOUNT_FILE: GCP Service Account Key file (path)

GCLOUD_PROJECT : The GCP Project ID to use

Examples :
```bash
export GOOGLE_APPLICATION_CREDENTIALS=~/.gcp/creds/ci-123456-213.json
export GCP_SERVICE_ACCOUNT_FILE=$GOOGLE_APPLICATION_CREDENTIALS

export GCLOUD_PROJECT=ci-123456
```