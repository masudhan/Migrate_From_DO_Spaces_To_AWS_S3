# Migrate-from-DO_Spaces-to-AWS_S3
## Tools we need
1. Install rclone 
    For macOS, `brew install rclone` 
    For windows, https://rclone.org/downloads/
    For other linux distributions, `curl https://rclone.org/install.sh | sudo bash`
2. AWS CLI - https://docs.aws.amazon.com/cli/latest/userguide/getting-started-install.html
3. Stable internet connection

## What next?
1. Generate New Key - https://cloud.digitalocean.com/account/api/tokens (Don't Generate Token it's Key)
2. For your IAM account, better to have S3 full access and generate aws_access_key_id, aws_secret_access_key and aws_session_token (for organisation we'll have this)
    If you want to migrate 1000GB's of data then aws_session_token should definetly set to 12 hours, that can be done from here - 
