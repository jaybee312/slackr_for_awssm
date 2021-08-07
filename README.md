# slackr_for_awssm
Run this in Sagemaker for basic slack connection, custom slack app required, see slackr docs for details

```{r}
install.packages("slackr")
library(slackr)

slackr_bot(paste('Test message', Sys.Date()), 
#           channel = '#rshtuff',
           #username = 'mrkaye97',
           #icon_emoji = 'tada'          
incoming_webhook_url = 'https://hooks.slack.com/services/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')

```
