Bronze Bucket Name - yt-data-pipeline-bronze-ameya 
Silver Bucket Name - yt-data-pipeline-silver-ameya
Gold Bucket Name - yt-data-pipeline-gold-ameya

Script Bucket - yt-data-pipeline-scripts-ameya

SNS ARN - arn:aws:sns:ap-south-1:905367995390:yt-data-pipeline-alerts-am:a6f43f79-c552-4bf9-b939-5b24bc952a79

Glue Bronze - yt_pipeline_bronze_am
Glue Gold - yt_pipeline_gold_am
Glue Silver - yt_pipeline_silver_am

--bronze_database yt_pipeline_bronze_am
--bronze_table raw_statistics
--silver_bucket yt-data-pipeline-silver-ameya
--silver_database yt_pipeline_silver_am
--silver_table clean_statistics

--silver_database yt_pipeline_silver_am
--gold_bucket yt-data-pipeline-gold-ameya
--gold_database yt_pipeline_gold_am

