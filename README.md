mongodb-s3-backup
=================

A simple shell script to backup a mongodb database to Amazon S3

This script is sligthly modified from the original, written by Lazaro Lima.

See his article from instructions: http://www.codeproject.com/Tips/547759/Automating-backup-for-MongoDB-using-CRON-and-S3CMD

I have just added the ability to backup password-protected databases and to remove the backup archives after they are uploaded to S3.
