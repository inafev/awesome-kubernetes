# Jenkins Alternatives for Continuous Integration
- [Alternatives](#alternatives)
- [Cloud Native CI/CD](#cloud-native-cicd)
- [Comparisons](#comparisons)
- [Integration with other CI/CD engines](#integration-with-other-cicd-engines)
## Alternatives
* [Cloudbees Flow](https://www.cloudbees.com/products/flow/overview)
* [Circle CI](https://circleci.com/)
    * [Getting started with Kubernetes: how to set up your first cluster](https://circleci.com/blog/getting-started-with-kubernetes-how-to-set-up-your-first-cluster/)
    * [Adding approval jobs to your CI pipeline](https://circleci.com/blog/adding-approval-jobs-to-your-ci-pipeline/)
* [Travis CI](https://travis-ci.org/)
* [Concourse](https://concourse-ci.org/)
    * [Building a continious deployment pipeline with Kubernetes and Concourse-CI](https://blog.alterway.fr/en/building-a-continious-deployment-pipeline-with-kubernetes-and-concourse-ci.html)
* [GoCD](https://www.gocd.org/)
* [Codefresh](https://codefresh.io/)
* [skaffold](https://skaffold.dev/)
* [JFrog Pipelines](https://jfrog.com/pipelines/)
* [Atlassian CI/CD](https://www.atlassian.com/continuous-delivery)
     * [Bamboo](https://www.atlassian.com/software/bamboo)
* [GitLab CI](https://dzone.com/articles/gitlab-ci-with-docker-environment-variable-quirks)
* [GitHub Actions CI/CD](https://github.blog/2019-08-08-github-actions-now-supports-ci-cd/)
    * [docs.github.com: Learn GitHub Actions](https://docs.github.com/en/actions/learn-github-actions)
    * [blog.bitsrc.io: Github Actions or Jenkins? Making the Right Choice for You](https://blog.bitsrc.io/github-actions-or-jenkins-making-the-right-choice-for-you-9ac774684c8) GitHub Actions and Jenkins both get the job done. Let’s find out whether it’s worth considering moving from Jenkins.
    * [openshift.com: Deploying to OpenShift using GitHub Actions](https://www.openshift.com/blog/deploying-to-openshift-using-github-actions)
    * [particule.io: Automatic build with Github Actions and Github Container Registry](https://particule.io/en/blog/cicd-github-registry/)
    * [proandroiddev.com: Improving CI/CD pipeline for Android via Fastlane and GitHub Actions](https://proandroiddev.com/improving-ci-cd-pipeline-for-android-via-fastlane-and-github-actions-a635162d2c53)
    * [redhat-actions](https://github.com/redhat-actions)
    * [redhat-actions/openshift-actions-runner](https://github.com/redhat-actions/openshift-actions-runner)
        * [redhat.com: Red Hat and GitHub Collaborate to Expand the Developer Experience on Red Hat OpenShift with GitHub Actions](https://www.redhat.com/en/about/press-releases/red-hat-and-github-collaborate-expand-developer-experience-red-hat-openshift-github-actions) Industry’s leading enterprise Kubernetes platform now integrates with GitHub, bringing DevOps automation tools from the world’s largest developer platform into the OpenShift ecosystem
    * [Awesome GitHub Actions](https://github.com/sdras/awesome-actions)
    * [yokawasa/action-setup-kube-tools](https://github.com/yokawasa/action-setup-kube-tools) A GitHub Action that setup Kubernetes tools (kubectl, kustomize, helm, kubeval, conftest, yq) and cache them on the runner. It is like a typescript version of stefanprodan/kube-tools with no command input param, but it's very fast as it installs the tools asynchronously.
    * [summerwind/actions-runner-controller](https://github.com/summerwind/actions-runner-controller) This controller operates self-hosted runners for GitHub Actions on your Kubernetes cluster.
* [Prow](https://github.com/kubernetes/test-infra/tree/master/prow)
* [Agola](https://agola.io/)
* [keptn](https://keptn.sh/) Keptn not only orchestrates Continuous Deployment, but it also orchestrates Continuous or Automated Operations.    
    * [dynatrace.com: What is keptn, how it works and how to get started!](https://www.dynatrace.com/news/blog/what-is-keptn-how-it-works-and-how-to-get-started/) 
    * [medium: Keptn 0.6.0 — My top 5 favorite improvements](https://medium.com/keptn/keptn-0-6-0-my-top-5-favorite-improvements-242d8ac1abfe)
    * [Quick Start](https://keptn.sh/docs/quickstart/)
    * [altoros.com: Automating Event-Based Continuous Delivery on Kubernetes with keptn](https://www.altoros.com/blog/automating-event-based-continuous-delivery-on-kubernetes-with-keptn/)
* [harness.io](https://harness.io/)
* [Drone](https://drone.io/)
* [Shippable (now part of JFrog Pipelines)](https://www.shippable.com/)
    * [JFrog Pipelines](https://jfrog.com/pipelines/)
* [Buildbot](https://buildbot.net/)
* [AWS DevOps - CICD](https://aws.amazon.com/devops/#cicd)
* [Google Cloud Build](https://cloud.google.com/cloud-build)
* [Azure DevOps](https://azure.microsoft.com/services/devops/)
* [Kubeflow](https://www.kubeflow.org/) The Machine Learning Toolkit for Kubernetes
* [shuttleOps](https://www.shuttleops.io/)
  * [thenewstack.io: ShuttleOps: No-Code Docker and Kubernetes](https://thenewstack.io/shuttleops-no-code-docker-and-kubernetes/)
* [HashiCorp Waypoint](https://www.waypointproject.io/)
  * [hashicorp.com: Announcing HashiCorp Waypoint](https://www.hashicorp.com/blog/announcing-waypoint)
* [onedev](https://github.com/theonedev/onedev)
    * [Hands-on GitOps with OneDev and Kubernetes](https://robinshen.medium.com/hands-on-gitops-with-onedev-f05bd278f07c)
* [lambdatest.com: 21 Of The Best Jenkins Alternatives For Developers](https://www.lambdatest.com/blog/best-jenkins-alternatives/)

## Cloud Native CI/CD
* [jenkins-x.io](https://jenkins-x.io/)
    * [cloudbees.com: what is jenkins-x](https://www.cloudbees.com/jenkins-x/what-is-jenkins-x)
    * [devopstoolkitseries.com](https://www.devopstoolkitseries.com/)
        * [youtube: Jenkins X: The Recipe For Continuous Delivery](https://www.youtube.com/watch?v=ihHr-iLfEGo)
    * [Book: The DevOps 2.6 Toolkit: Jenkins X](https://leanpub.com/the-devops-2-6-toolkit)
* [spinnaker.io](https://www.spinnaker.io/)
    * [Deploy Spinnaker CD Pipelines in Kubernetes](https://www.opsmx.com/blog/deploy-spinnaker-cd-pipelines-in-kubernetes/)
    * [speakerdeck.com: Introduction to Spinnaker Managed Pipeline Templates](https://speakerdeck.com/keisukeyamashita/introduction-to-spinnaker-managed-pipeline-templates)
    * [speakerdeck.com: Spinnaker Application management by Terraform Plugins](https://speakerdeck.com/keisukeyamashita/spinnaker-application-management-by-terraform-plugins)
    * [medium: Spinnaker The Hard Way](https://medium.com/searce/spinnaker-the-hard-way-278913f3f1d8)
    * [opensource.com: Why Spinnaker matters to CI/CD](https://opensource.com/article/19/8/why-spinnaker-matters-cicd) Spinnaker provides unique building blocks to create tailor-made, and highly-collaborative continuous delivery pipelines. 
    * [medium: How we rolled out our Kubernetes platform in Adevinta Spain](https://medium.com/adevinta-tech-blog/how-we-rolled-out-our-kubernetes-platform-in-adevinta-spain-63495884a1db)
* [ArgoCD](https://argoproj.github.io/argo-cd/) Declarative GitOps CD for Kubernetes
    * [Cloud Native Computing Foundation Accepts Argo as an Incubator Project](https://www.intuit.com/blog/technology/cloud-native-computing-foundation-accepts-argo-as-an-incubator-project/)
    * [openshift.com: OpenShift Authentication Integration with ArgoCD](https://www.openshift.com/blog/openshift-authentication-integration-with-argocd)
    * [developers.redhat.com: OpenShift joins the Argo CD community (KubeCon Europe 2020)](https://developers.redhat.com/blog/2020/08/17/openshift-joins-the-argo-cd-community-kubecon-europe-2020/)
    * [thenewstack.io: Applied GitOps with ArgoCD](https://thenewstack.io/applied-gitops-with-argocd/)
    * [IBM/argocd-vault-plugin](https://github.com/IBM/argocd-vault-plugin) An ArgoCD plugin to retrieve secrets from Hashicorp Vault and inject them into Kubernetes secrets.
* [Tekton](https://github.com/tektoncd/)
    * [Tekton PetClinic Demo](https://github.com/tektoncd/pipeline)
    * [Tekton PetClinic Demo Youtube](https://www.youtube.com/watch?v=igwFpZOUTnw)
    * [OpenShift Tekton pipelines](https://www.openshift.com/learn/topics/pipelines)
    * [developers.redhat.com: An introduction to cloud native CI/CD with Red Hat OpenShift pipelines](https://developers.redhat.com/blog/2019/07/18/an-introduction-to-cloud-native-ci-cd-with-red-hat-openshift-pipelines/)
    * [blog.openshift.com: cloud native CI/CD with openshift pipelines](https://blog.openshift.com/cloud-native-ci-cd-with-openshift-pipelines/) 
    * [learn.openshift.com/middleware/pipelines](https://learn.openshift.com/middleware/pipelines/)
* [Jenkins-X + Tekton on OpenShift](https://github.com/openshift/tektoncd-pipeline-operator)
    * [CI/CD OpenShift and Tekton](https://blog.sonatype.com/new-cloud-native-ci/cd-projects-openshift-and-tekton)
    * [github.com/openshift/pipelines-tutorial](https://github.com/openshift/pipelines-tutorial)
    * [https://github.com/jenkins-x/jenkins-x-openshift-image](https://github.com/jenkins-x/jenkins-x-openshift-image)
    * [medium: Dailymotion’s journey from Jenkins to Jenkins X](https://medium.com/dailymotion/from-jenkins-to-jenkins-x-604b6cde0ce3)
* HAT is the acronym for Helm, ArgoCD and Tekton:
    * [empathy.co: HAT: CI/CD for Deploying Cloud Native Applications](https://www.empathy.co/blog/hat-ci-cd-for-deploying-cloud-native-applications/) 

## Comparisons
* [dzone: Which CI is Best For My Team?](https://dzone.com/articles/which-ci-is-best-for-my-team)
* [inovex.de: Spinnaker vs. Argo CD vs. Tekton vs. Jenkins X: Cloud-Native CI/CD](https://www.inovex.de/blog/spinnaker-vs-argo-cd-vs-tekton-vs-jenkins-x/)
* [medium: Top 7 Best CI/CD Tools you should get your hands on in 2020](https://medium.com/devops-dudes/top-7-best-ci-cd-tools-you-should-get-your-hands-on-in-2020-832c29db936a)
* [dzone: Jenkins vs GitLab CI: Battle of CI/CD Tools](https://dzone.com/articles/jenkins-vs-gitlab-ci-battle-of-cicd-tools) The battle of CI/CD tools rages on — come and find out which is the right tool for your DevOps testing needs.
* [lambdatest.com: TeamCity vs. Jenkins: Picking The Right CI/CD Tool](https://www.lambdatest.com/blog/teamcity-vs-jenkins-picking-the-right-ci-cd-tool/)
* [lambdatest.com: Bamboo vs Jenkins: Showdown Of CI/CD Tools](https://www.lambdatest.com/blog/bamboo-vs-jenkins-showdown-of-ci-cd-tools/)

## Integration with other CI/CD engines
* [CloudBees Integrates Software Delivery Management Platform With Google Cloud Build and Tekton to Break Down Development Silos](https://www.previous.cloudbees.com/press/cloudbees-integrates-software-delivery-management-platform-google-cloud-build-and-tekton-break)

---
<center>
[![gitlab](images/gitlab.jpg)](https://gitlab.com/)
</center>

<center>
<blockquote class="twitter-tweet"><p lang="en" dir="ltr">THREAD: Is it possible that Kubeflow pipeline is one of the best CI/CD tools for Kubernetes?<br><br>I spent some time playing with Kubernetes &amp; <a href="https://twitter.com/kubeflow?ref_src=twsrc%5Etfw">@kubeflow</a> pipelines, and they have one feature which is just great:<br><br>You can define the pipeline with real code! <a href="https://t.co/gNDzvvkCij">pic.twitter.com/gNDzvvkCij</a></p>&mdash; Daniele Polencic (@danielepolencic) <a href="https://twitter.com/danielepolencic/status/1285929877493800961?ref_src=twsrc%5Etfw">July 22, 2020</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

<script async class="speakerdeck-embed" data-id="4792e3bc2f474efb8589d231314091e8" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script>
</center>