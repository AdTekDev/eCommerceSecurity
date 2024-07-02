
# FAR FRR 

FRR (also called Type I error) is the likelihood that a legitimate user will be rejected by the system; for example, a 10% FRR means that the system will reject 1 out of 10 genuine login attempts on average.   
FRR = number of false negatives ÷ (number of false negatives + number of true positives) x 100  

FAR (also called Type II error) is the likelihood that an impostor will be accepted by the system; for example, a 10% FAR means that the system will mistake 1 out of 10 impostors for a genuine user on average.   
FAR = number of false positives ÷ (number of false positives + number of true negatives) x 100  

![image](https://github.com/AdTekDev/eCommerceSecurity/assets/18588011/4cba76f0-1efb-4869-a517-1bfd081b0685)


## Example

### 01

Let’s say that we have a database of electronic signatures from 100 users, and for each user separately, we built and calibrated authentication models using a part of this database. We have exactly 5 signatures left from each user to test our model’s false rejection rate, which means that we can get 100 x 5 = 500 genuine scores in total. 
If we find that (for example) 20 of these scores are below the (user-specific) thresholds, FRR = ?

### 02

![image](https://github.com/AdTekDev/eCommerceSecurity/assets/18588011/7fa6dfde-ec3d-48af-ae8e-981cfb95c7e0)

FAR, FRR, Acc = ?
