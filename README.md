ansible-elasticsearch-klusters

## Usage
### Environment Variables

GOOGLE_APPLICATION_CREDENTIALS: GCP Service Account Key file (path)

GCLOUD_PROJECT : The GCP Project ID to use

Examples :
```bash
export GOOGLE_APPLICATION_CREDENTIALS=~/.gcp/creds/ci-123456-213.json
export GCLOUD_PROJECT=ci-123456
```

### Dependencies

Install dependencies :
```bash
pip install -r python_requirements.txt

ansible-galaxy install -f -r ansible_requirements.yml
```

### Execute playbook

Run kickstart.yml :
```bash
ansible-playbook -i inventories/test/ playbooks/elasticsearch/kickstart.yml
```
