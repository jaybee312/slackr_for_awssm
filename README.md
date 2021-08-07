# slackr_for_awssm
Run this in Sagemaker for basic slack connection, custom slack app required, see slackr docs for details

```{r}
install.packages("slackr")
library(slackr)

slackr_bot(paste('Test message', Sys.Date()),           
incoming_webhook_url = 'insert webhook from custom app here')

```
