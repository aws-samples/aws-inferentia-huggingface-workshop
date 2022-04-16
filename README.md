# AWS Summit San Francisco 2022
## CMP314 Optimizing NLP models with Amazon EC2 Inf1 instances in Amazon Sagemaker

Welcome to the AWS Summit San Francisco 2022 Inferentia Workshop!
During this workshop, we will create two endpoints with one HuggingFace model each. We will use them for the task of paraphrase detection which is an NLP classification problem. These two endpoints will have the following configurations: a) CPU-based endpoint, where we will be deploying the model with no changes; and b) Inf1 instance based endpoint, where we will prepare and compile the model using SageMaker Neo before deploying. Finally, we will perform a latency and throughput performance comparison of both endpoints. 

## Event engine access during the event
#### Follow these instructions to connect to the AWS Console during the event

1. Access event engine: Open a browser and type the URL shared during the workshop.

2. Click on “Agree” (make sure the event passcode is displayed)
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/accessevent.png" width="50%">

3. Click on “Email One-Time Password (OTP)”
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/signin.png" width="50%">

4. Complete with your email and click “Send Passcode”
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/email.png" width="50%">

5. Retrieve the OTP passcode from your email. Copy and paste it in the “Passcode 9 digit code” field. Press “Sign In”
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/otp.png" width="50%">

6. Once logged in, you will see the "team Dashboard". Click on “AWS Console”
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/teamdashboard.png" width="50%">

7. Then click on  “Open AWS Console"
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/openconsole.png" width="50%">

8. Inside the console look for the search box and Type “Sagemaker”, then click on the "Amazon Sagemaker" Service. If you prefer you can navigate directly to the Sagemaker console.
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/accesssm.png" width="50%">

9. Once you see the Sagemaker dashboard click on “Studio” on the “Sagemaker Domain” menu on the left.
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/menuleft.png" width="50%">

10. Click on “Launch App” button and then on “Studio”
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/accessstudio.png" width="50%">

11. Once inside Sagemaker Studio”, go to “File/New/Terminal” to open a terminal:
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/terminal.png" width="50%">

12. Type the following command to clone this repo:
`git clone https://github.com/aws-samples/aws-inferentia-huggingface-workshop.git`

13. Once the repo is cloned, open the Jupiter notebook named [aws_summit_2022_inf1_bert_compile_and_deploy.ipynb](https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/aws_summit_2022_inf1_bert_compile_and_deploy.ipynb). To do this, find the file browser on the left, and click on “aws-inferentia-huggingface-workshop” then double click on the file name **aws_summit_2022_inf1_bert_compile_and_deploy.ipynb**. 
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/opennb.png" width="50%">

14. You will see the following pop up. 
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/kernel.png" width="50%">

15. Make sure you select the Python 3 (Pytorch 1.8 Python 3.6 CPU Optimized) Kernel when prompted
<img src="https://github.com/aws-samples/aws-inferentia-huggingface-workshop/blob/main/images/kernelselect.png" width="50%">

# Now start the workshop and have fun ! 




## Licence

This code is released under the MIT-0 license
Please refer to the license for applicable terms.
