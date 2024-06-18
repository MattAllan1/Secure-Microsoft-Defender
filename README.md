# Secure Your Cloud with Microsoft Defender for Cloud

## Objective

1. Use Microsoft Defender for Cloud to identify the network, compute, storage, and application security risks in your Azure environment
2. Follow Microsoft Defender for Cloud's recommendations to mitigate risks
3. Resolve several common security issues

Before completing the Lab instructions, the environment will look as follows:

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/daf60afc-627f-4a75-a834-8971550366cb)

After completing the Lab instructions, the environment should look similar to:

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/4db55bf0-f054-4e3b-bd30-4c8f64152ea0)

### Skills Learned

- Microsoft Defender for Cloud (previously Azure Security Center)

### Tools Used

- Microsoft Azure Portal
- Microsoft Defender for Cloud (previously Azure Security Center)

## Step 1 - Inspecting the Insecure Lab Resources

In the search bar, type Resource groups and navigate to the only available resource group

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/6bf344e8-8c10-47d9-8b71-8a6a368778ec)

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/88bddd99-94e7-4160-8944-21c94f1d36e3)

This takes us to the Overview page

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/38c3f72c-629f-4e19-b929-7121ce79fb5a)

From the resources table were clicking on the 'Storage Account'

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/ddb4f00f-407c-4d71-bda9-18679481d355)

In the Storage account menu, click on Configuration under Settings

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/dc2c6e99-17cf-4a9f-86f0-e324f99852d7)

This takes us to the following page

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/25dabb4e-3ba5-4a20-8740-570dc1ab45a1)

The 'Secure transfer required' setting is relevant to this lab. It requires a secure HTTPS connection to be used for any storage account requests. HTTPS secures data in transit, meaning data that is transferred over the network.

![image](https://github.com/MattAllan1/Secure-Microsoft-Defender/assets/172419505/61987091-913a-4d34-9188-bc40610f13f3)







