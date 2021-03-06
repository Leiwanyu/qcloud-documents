
## Applying for Domain Validation (DV) SSL Certificate

## 1. Application Entry

Enter the SSL certificate management console
![](https://mc.qcloudimg.com/static/img/f990389699184b164082dce1ebe809c6/1.png)

Click "Apply for Certificate"
![](https://mc.qcloudimg.com/static/img/4efe78b416cc29cacba1cbc2ba475bb6/2.png)

View the model of the applied domain validation certificate, and click "OK"

![](https://mc.qcloudimg.com/static/img/287bd4f6c633cb1a81e18a096f47d5ed/3.png)

## 2. Filling in the Application

Fill in the applied domain, note that it is not supported to apply for top-level domains (e.g. qcloud com), please enter second-level, third-level domains such as cloud.tencent.com, demo.test.qlcoud.com.
![](https://mc.qcloudimg.com/static/img/4961164252cd488c9695475e173c0b8c/4.png)

## 3. DNS Verification
### 3.1 Manual DNS Verification

Certificates support manual DNS verification by default, please refer to [Details](https://cloud.tencent.com/doc/product/400/4142#2.-.E6.89.8B.E5.8A.A8dns.E9.AA.8C.E8.AF.81) for detailed verification method.
![](https://mc.qcloudimg.com/static/img/2f90c6cdf51ec98ba0fd7a112a891e13/5.png)

### 3.2 Choosing Automatic DNS Verification

If [Cloud Resolution Platform](https://console.cloud.tencent.com/cns/domains) is added successfully for the applied domain, the domain will support automatic DNS verification. Refer to [Details](https://cloud.tencent.com/doc/product/400/4142#1.-.E8.87.AA.E5.8A.A8dns.E9.AA.8C.E8.AF.81) for detailed verification method.
![](https://mc.qcloudimg.com/static/img/8c10bfb9fa50a520e0b8b45f3b7a9f74/6.png)

## 4. Submitting the Application
### 4.1 Identity Verification after Submission

When application is successfully submitted, a pop-up window will appear, notifying that you need to go to the "Certificate Detail Page" to obtain the CName record and add resolution:
![](https://mc.qcloudimg.com/static/img/7d99496ed47a163a3ee25c728187bf45/7.png)

The process of obtaining the CName record is shown in Tips, please add resolution as soon as possible so that it can be approved by CA:
![](https://mc.qcloudimg.com/static/img/1f0d7d113cd4ee14cda423a32e853fe4/8.png)

### 4.2 Failed to Submit Application

The pop-up window shown below indicates that the submitted domain is not approved by CA's security verification. Refer to [Reasons for Failed Security Verification](https://cloud.tencent.com/doc/product/400/5439) for detailed reasons.
![](https://mc.qcloudimg.com/static/img/25451d24cf3c717454830a44925642ec/1.png)

