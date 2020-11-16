---
layout: post
title:  "High level challenges"
date:   2020-10-12 14:26:29 +0300
categories: jekyll update
---

<header style="margin-top: -188px; position: absolute;">
   <a href="https://metatavu.fi">
   <img src="/xamk-challenges/media/metatavu-logo.png" style="max-width: 100px;"
      alt="Jekyll logo" />
   </a>
</header>

#### High level challenges will demonstrate you the principles of cluster autoscaling. You will continue using Azure Kubernetes environment in this step. Please use your free Azure credit wisely, wrong configuration for autoscaling can spend it quickly. While completing these tasks, you will get to know what an Azure Kubernetes cluster autoscaler is and how to configure it. Knowledge gained during this level challenges completion will let you create scalable Kubernetes clusters in future. You can submit as many proofs of completion as you have achieved after completing this tier. **Extra** proof will become a great bonus for you. Good luck!

#### Challenge instructions:

- Use an existing Azure Kubernetes cluster

- Make sure it is running and FoldingAtHome application is displayed when navigating to Service IP address

- Configure th Azure Kubernetes cluster auto-scaler with 2 Nodes limit and 1 Node by default

- Make sure cluster auto-scaler works when load in the FoldingAtHome application is increased

- ```Tip: experiment with a Horizontal Pod autoscaler setup```

- Resize the load and see how your Nodes scale up and down

- Submit a proof of completion

#### Proof of completion:

See the steps below and fill a form based on them

- Provide a configuration file or command used for creating an Azure Kubernetes cluster auto-scaler  in any ```text file``` format or ```.yaml```

- Execute terminal command ```kubectl get nodes``` **without** load. It should display one Node. Provide a screenshot containing command and it's output.

- Execute terminal command ```kubectl get nodes``` **with** load generated. It should display two Nodes. Provide a screenshot containing command and it's output.

- Execute terminal command ```kubectl top nodes``` **with** load generated. It should display two Nodes and their metrics. Provide a screenshot containing command and it's output.

- **Extra:** Upload a screen recording video showing how your nodes scale up and down under a load. Efficiency and time are taken into account 😀

- ```Note: remember to stop the load generation to avoid spending all the credit```

- Send a glorious message in the Slack challenges channel that Tier 4 is completed

#### [Please submit your proofs of completion here. Should be done once after each challenges tier.](https://docs.google.com/forms/d/e/1FAIpQLSdJM5bxK2b_DFY8RLxKc83oFzKWBh_eu8WZ9rJHfBOqI-sqbQ/viewform?usp=sf_link){:target="_blank"}
