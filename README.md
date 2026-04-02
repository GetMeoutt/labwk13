# terraform-s3-backend-lab

- Nuree Na
- Noppanat Sripan

**When is the state file created?**
- after `terraform apply` completes


**When is the lock file present?**
- it stays there while running `terraform apply` between entering the command and we typing in `yes`


**Is the lock file always in the bucket after it is created?**
- No it is automatically deleted after the apply finishes


**Take a screenshot of the AWS S3 web console that shows the state file only.**
<img width="2151" height="717" alt="state-file" src="https://github.com/user-attachments/assets/7084a441-4124-4830-9e80-55548ee4972f" />

**Take a screenshot of the AWS S3 web console that shows the lock file and the state file.**
<img width="2190" height="656" alt="lock-file" src="https://github.com/user-attachments/assets/90cdbb81-4e2f-4dcd-ae82-6825004e3ed4" />
