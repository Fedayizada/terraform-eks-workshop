---
title: "Second VPC - with one Character !" 
date: 2018-10-03T10:14:46-07:00
draft: false
weight: 61
---

## Creating a third VPC by changing one character !

Next we are going to observe some of the advantages you can get with  Infrastructure as code - provided it is properly paramatised.

Edit the variables.tf file and change the value of mycount from 1 to 2


![tf 1-2](/images/andyt/tf-1-2.png)


rerun terrafom plan and apply.

```
terraform plan -out tfplan
```

```
terraform apply tfplan
```


What happens , what has been created - look in the console?

:white_check_mark: Proceed to the next step