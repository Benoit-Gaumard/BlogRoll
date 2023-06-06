# BlogRoll

A curated list of  blogs, videos, tutorials, code, tools & scripts, related to the design and implementation of solutions in Microsoft Azure.

This list contains anything that can help with your **Microsoft Azure architecture** and quickly get you up and running when designing, planning, and implementing services that empower organisations around the planet to achieve more.

> Community contributions are most welcome! Feel free to submit a **pull request** with any adds/removes/changes to content!

## Table Of Contents

- [Certifications](#medal_sports-Certifications)
- [FinOps](#euro-FinOps)
- [Informations](#information_source-Informations)
- [Services](#information_source-Services)
- [Policies](#cop-Policies)
- [Services state](#sun_behind_small_cloud-Services-state)
- [Cloud Services Comparison](#heavy_plus_sign-Cloud-Services-Comparison)
- [DevOps](#rocket-DevOps)
- [Azure Active Directory](#large_blue_diamond-Azure-Active-Directory)
- [Misc](#open_file_folder-Misc)
- [Sustainability](#seedling-Sustainability)
- [HA and DR](#cloud-HA-and-DR)
- [Architecture](#classical_building-Architecture)
- [Support](#house-Support)
- [Governance](#house-Governance)
- [Tags](#label-Tags)
- [Videos](#books-Videos)
- [DashBoards](#books-DashBoards)
- [GitHub](#octocat-GitHub)
- [Stencils and icons](#black_nib-Stencils-and-icons)
- [Tips and tricks](#page_with_curl-tips-and-tricks)
- [LightHouse](#statue_of_liberty-lighthouse)
- [Compliance](#police_car-compliance)
- [Virtual Machines](#computer-virtual-machines)
- [Virtual Machines Scale Set (VMSS)](#arrow_upper_right-Virtual-Machines-Scale-Set-(VMSS))
- [ARM](#a-arm)
- [Analytics and monitoring](#stopwatch-Analytics-and-monitoring)
- [Security](#ninja-security)
- [Terraform](#technologist-terraform)
- [Bicep](#muscle-Bicep)
- [Web](#earth_africa-web)
- [Network](#globe_with_meridians-network)
- [KQL Queries](#page_with_curl-kql_queries)

> Links below are from official and custom sources.

## :medal_sports: Certifications

[Back To Top](#Table-Of-Contents)

- [Official certifications training poster](https://aka.ms/TrainCertPoster) :fire:
- [Browse Certifications by roles](https://learn.microsoft.com/en-us/certifications/)
- [Microsoft Learn](https://docs.microsoft.com/en-us/learn/)
- [Exam Sandbox, demo the Microsoft exam experience](https://aka.ms/examdemo)
- [Microsoft learn community](https://techcommunity.microsoft.com/t5/microsoft-learn/ct-p/MicrosoftLearn)
- [Practice Assessments for Microsoft Certifications](https://learn.microsoft.com/en-us/certifications/practice-assessments-for-microsoft-certifications)
- [Practice Assessments for Microsoft Certifications 2](https://techcommunity.microsoft.com/t5/microsoft-learn-blog/prep-for-certification-exams-with-free-practice-assessments-on/ba-p/3666866)
- [Azure Deployment Environments](https://techcommunity.microsoft.com/t5/azure-developer-community-blog/introducing-azure-deployment-environments/ba-p/3412095)


## :euro: FinOps

[Back To Top](#Table-Of-Contents)

- [Total Cost of Ownership (TCO) Calculator](https://azure.microsoft.com/en-us/pricing/tco/calculator/)
- [Azure Pricing calculator](https://azure.microsoft.com/en-us/pricing/calculator/) :fire:
- [Strategies to realizing Cost Savings in Azure](https://docs.microsoft.com/fr-fr/archive/blogs/girishp/strategies-to-realizing-cost-savings-in-azure)
- [Budget Alert in Teams](https://github.com/Azure/AzureBudgetAlert-in-Teams)
- [Azure Optimization Engine (AOE)](https://github.com/helderpinto/AzureOptimizationEngine)
- [Microsoft Defender for Cloud Price Estimation Dashboard](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/microsoft-defender-for-cloud-price-estimation-dashboard/ba-p/3247622)
- [Cost optimization pillar](https://docs.microsoft.com/en-us/azure/architecture/framework/cost/overview)
- [Azure Cost Reporting PBI](https://github.com/chris-bowman/Azure-Cost-Reporting/tree/main/Power%20BI%20Report)
- [Project Bose: Cost of an Enterprise by cost centers, divisions](https://techcommunity.microsoft.com/t5/azure-architecture-blog/codename-project-bose-calculate-azure-cost-of-an-enterprise-by/ba-p/3741295)
- [The Azure FinOps guide](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/the-azure-finops-guide/ba-p/3704132)
- [Azure Cost Cli](https://github.com/mivano/azure-cost-cli)


## :information_source: Informations

[Back To Top](#Table-Of-Contents)

- [Azure Updates](https://azure.microsoft.com/en-us/updates/) :fire:
- [Azure Info Hub](https://azureinfohub.azurewebsites.net/)
- [Azure Weekly](https://azureweekly.info/)
- [AzureFeeds](https://azurefeeds.com/)
- [Official Microsoft Team Blogs](https://docs.microsoft.com/en-us/archive/blogs/blogms/official-microsoft-team-blogs-microsoft-blogs) :fire:

## :information_source: Services

[Back To Top](#Table-Of-Contents)

- [Azure Charts](https://azurecharts.com/) :fire:
- [Azure Periodic table](https://azureperiodic.data3.com)
- [Azure Services io](https://azureservices.io)
- [Azure deprecation DashBoard](https://github.com/azure-deprecation/dashboard/issues)
- [Azure Charts Deprecations](https://azurecharts.com/timeboards/deprecations)
- [Azure Charts Arrivals](https://azurecharts.com/timeboards/arrivals)


## :cop: Policies

[Back To Top](#Table-Of-Contents)

- [Windows using Guest Configuration](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/7-steps-to-author-develop-and-deploy-custom-recommendations-for/ba-p/3166026)
- [Azure Policy As Code](https://github.com/Azure/enterprise-azure-policy-as-code)
- [Policy-as-code with Azure Pipelines](https://medium.com/microsoftazure/devsecops-policy-as-code-with-azure-pipelines-86cc1e27f03c)
- [Policy Distribution Dashboard for Microsoft Defender for Cloud](https://techcommunity.microsoft.com/t5/microsoft-defender-for-cloud/policy-distribution-dashboard-for-microsoft-defender-for-cloud/ba-p/3264712)
- [Ryan Graham GitHub Repo](https://github.com/rjygraham/AzurePolicy/tree/main/Samples)
- [tyconsulting GitHub Repo](https://github.com/tyconsulting/azurepolicy)
- [Azure Community Policy GitHub Repo](https://github.com/Azure/Community-Policy) :fire:
- [Azure Policy Compliance WorkBook](https://www.cloudsma.com/2021/10/build-azure-policy-compliance-workbook/)
- [AWESOME-Azure-Policy](https://github.com/globalbao/awesome-azure-policy)
- [Azure Diagnostics Policy Generator](https://github.com/JimGBritt/AzurePolicy/tree/master/AzureMonitor/Scripts)
- [Configure centralized policy management](https://www.cloudpartner.fi/?p=7015)
- [Policies Aliases List](https://policyalias.mats.codes/)

## :sun_behind_small_cloud: Services state

[Back To Top](#Table-Of-Contents)

- [Azure Status](https://status.azure.com/) :fire:
- [New Azure Status](https://azure.status.microsoft/en-us/status) :fire:
- [Azure Infrastructure Map](https://infrastructuremap.microsoft.com/) :fire:
- [Azure Speed Test 2.0](http://azurespeedtest.azurewebsites.net)
- [AzSpeedTest Powershell](https://github.com/devblackops/AzSpeedTest)
- [AzureSpeed](https://www.azurespeed.com/)

## :heavy_plus_sign: Cloud Services Comparison

[Back To Top](#Table-Of-Contents)

- [Public Cloud Services Comparison](https://comparecloud.in/)
- [Azure VM Comparison](https://azureprice.net/)
- [Compare AWS and Azure services to Google Cloud](https://cloud.google.com/free/docs/aws-azure-gcp-service-comparison?utm_source=google&utm_medium=blog&utm_campaign=FY21-Q2-Product-Mapping-Blog&utm_content=documentation)
- [Compare Azure and AWS services](https://docs.microsoft.com/en-us/azure/architecture/aws-professional/services)
- [Azure MarketPlace](https://azuremarketplace.microsoft.com/en-us/)

## :rocket: DevOps

[Back To Top](#Table-Of-Contents)

- [Learn git branching](https://learngitbranching.js.org/) :fire:
- [Vinijmoura GitHub Repo](https://github.com/vinijmoura/Azure-DevOps)
- [Azure DevOps Labs](https://azuredevopslabs.com)
- [Azure DevOps Demo Generator](https://azuredevopsdemogenerator.azurewebsites.net)
- [Azure DevOps Organization](https://aex.dev.azure.com/) :fire:
- [Devops Resources](https://github.com/bregman-arie/devops-resources)
- [Devops Bookmark](http://www.devopsbookmarks.com/cloud-paas)
- [Devops roadmap](https://roadmap.sh/)
- [The Microsoft Azure Developer's Cheat Sheet](https://github.com/milanm/azure-cheat-sheet)
- [awesome-french-devops](https://github.com/stephrobert/awesome-french-devops/)
- [Stéphane Robert Blog](https://blog.stephane-robert.info/)

## :large_blue_diamond: Azure Active Directory

[Back To Top](#Table-Of-Contents)

- [Azure AD where is your data located](https://msit.powerbi.com/view?r=eyJrIjoiODdjOWViZDctMWRhZS00ODUzLWI4MmQtNWM5NjBkZTBkNjFlIiwidCI6IjcyZjk4OGJmLTg2ZjEtNDFhZi05MWFiLTJkN2NkMDExZGI0NyIsImMiOjV9)
- [Tenant availability check 1](https://account.azure.com/organization)
- [Tenant availability check 2](https://o365.rocks/)
- [Azure AD pricing](https://azure.microsoft.com/en-us/pricing/details/active-directory/)
- [Interactive authentication](https://microsoft.com/devicelogin/)
- [Azure Active Directory admin center](http://aad.portal.azure.com) :fire:
- [Azure AD Exporter](https://github.com/microsoft/azureadexporter/)
- [Azure AD Big Picture](https://raw.githubusercontent.com/msandbu/azuread/main/AzureAD%20Big%20picture.jpg)
- [Microsoft Graph Changelog](https://developer.microsoft.com/en-us/graph/changelog/?search=)
- [Azure AD Security Config Analyzer (AADSCA)](https://github.com/Cloud-Architekt/AzureAD-Attack-Defense/blob/main/AADSecurityConfigAnalyzer.md)
- [Azure-AccessPermissions](https://github.com/csandker/Azure-AccessPermissions)

## :open_file_folder: Misc

[Back To Top](#Table-Of-Contents)

- [Azure Mask](https://github.com/clarkio/azure-mask)
- [Raspberry Simulator for IOT Hub](https://docs.microsoft.com/en-us/azure/iot-hub/iot-hub-raspberry-pi-web-simulator-get-started)
- [sqlflow](https://sqlflow.gudusoft.com/#/)
- [Nuage de mots](https://nuagedemots.co/)

## :seedling: Sustainability

[Back To Top](#Table-Of-Contents)

- [Microsoft Emissions Impact Dashboard](https://azure.microsoft.com/es-es/blog/empowering-cloud-sustainability-with-the-microsoft-emissions-impact-dashboard/)

## :cloud: HA and DR

[Back To Top](#Table-Of-Contents)

- [Azure Geographies and regions](https://azure.microsoft.com/en-us/global-infrastructure/geographies/)
- [Azure cross regions replication](https://docs.microsoft.com/en-us/azure/availability-zones/cross-region-replication-azure)
- [Azure regions and availability zones](https://docs.microsoft.com/en-us/learn/modules/azure-architecture-fundamentals/regions-availability-zones)

## :classical_building:  Architecture

[Back To Top](#Table-Of-Contents)

- [Microsoft Cloud Workshop library](https://microsoftcloudworkshop.com/)
- [White papers](https://azure.microsoft.com/en-us/resources/whitepapers/search/?type=WhitePaperResource)
- [Microsoft Cybersecurity Reference Architectures (MCRA)](https://docs.microsoft.com/en-us/security/cybersecurity-reference-architecture/mcra) :fire:
- [Azure subscription and service limits, quotas, and constraints](https://docs.microsoft.com/en-us/azure/azure-resource-manager/management/azure-subscription-service-limits)
- [Azure Cloud Adoption Framework (CAF)](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/) :fire:
- [Azure Well-Architected Framework](https://learn.microsoft.com/en-us/azure/architecture/framework/)
- [Azure Survival Guide](https://social.technet.microsoft.com/wiki/contents/articles/630.microsoft-azure-survival-guide.aspx)
- [Azure Subscription Design](https://social.technet.microsoft.com/wiki/contents/articles/33800.azure-iaas-v2-arm-design-series-azure-subscriptions.aspx)
- [Azure Offers](https://azure.microsoft.com/en-us/support/legal/offer-details/)
- [Subscription decision guide](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/decision-guides/subscriptions/)
- [Azure Built In roles](https://docs.microsoft.com/en-us/azure/role-based-access-control/built-in-roles)
- [Azure Reference Architectures](https://docs.microsoft.com/en-us/azure/architecture/browse/) :fire:
- [Cloud adoption antipatterns](https://docs.microsoft.com/en-us/azure/cloud-adoption-framework/antipatterns/antipatterns-to-avoid)
- [Azure Customer Advisory Team (CAT)](https://techcommunity.microsoft.com/t5/azure-global/bg-p/AzureCAT)
- [SLA for Azure services](https://azure.microsoft.com/en-us/support/legal/sla/summary/)
- [SLA Calculator](https://uptime.is/)
- [Azure Preview portal](https://preview.portal.azure.com)
- [Azure RC portal](https://rc.portal.azure.com/)
- [Microsoft portals](https://www.nuno-silva.net/microsoft-365-portals)
- [Microsoft portals 2](https://www.moderndeployment.com/microsoft-azure-management-urls/)
- [Azure portals 3](https://cmd.ms/)
- [Microsoft Administrator Portals](https://msportals.io)
- [MyApps](https://myapps.microsoft.com/)
- [Azure supported workloads](https://docs.microsoft.com/en-US/troubleshoot/azure/virtual-machines/server-software-support)
- [awesome-azure-architecture](https://github.com/lukemurraynz/awesome-azure-architecture)
- [Microsoft Assessments](https://docs.microsoft.com/en-us/assessments/?mode=home)
- [docsupdatetracker](https://docsupdatetracker.net/)
- [Landing Zone mission-critical](https://learn.microsoft.com/en-us/azure/architecture/reference-architectures/containers/aks-mission-critical/mission-critical-landing-zone)
- [Azure Quick Review](https://github.com/Azure/azqr)
- [Azure Sandbox](https://learn.microsoft.com/en-us/azure/architecture/guide/azure-sandbox/azure-sandbox)
- [CAF Additionnal resources](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-setup-guide/staying-current?tabs=AdditionalResources#tabpanel_1_AdditionalResources)
- [Cloud Adoption Framework Tools and Templates](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/resources/tools-templates)

## :house: Support

[Back To Top](#Table-Of-Contents)

- [Azure Support plans](https://azure.microsoft.com/en-us/support/plans/)
- [Azure community support](https://docs.microsoft.com/en-us/answers/products/azure?product=all)
- [Azure feedback](https://feedback.azure.com/d365community) :fire:

## :house: Governance

[Back To Top](#Table-Of-Contents)

- [AzAdvertizer](https://www.azadvertizer.net/) :fire:
- [AzGovViz](https://github.com/JulianHayward/Azure-MG-Sub-Governance-Reporting)
- [Continuous Cloud Optimization (CCO)](https://github.com/Azure/ccodashboard) :fire:
- [AzureSecurityCenterInventory](https://github.com/ASCI)
- [Azure Resource Inventory (ARI)](https://github.com/microsoft/ARI)
- [Azure Visualizer (AzViz)](https://github.com/PrateekKumarSingh/AzViz)
- [New (diagrams.net) diagram](https://powershell.today/2022/02/new-diagrams.net-diagram/)
- [Azure Raci toolkit](https://github.com/jkstant/AzureRACIToolkit)
- [Azure Naming Tool](https://github.com/microsoft/CloudAdoptionFramework/tree/master/ready/AzNamingTool)
- [Azure Periodic Table of Resource Naming Convention](https://justinoconnor.codes/2022/08/19/azure-periodic-table-of-resource-naming-convention-shorthands/) :fire:
- [The perfect Azure naming convention](https://www.devjev.nl/posts/2022/the-perfect-azure-naming-convention/)
- [Variables naming convention](https://juniortoexpert.com/fr/convention-de-denomination-des-variables/)

## :label: Tags

[Back To Top](#Table-Of-Contents)

- [Develop your naming and tagging strategy for Azure resources](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/ready/azure-best-practices/resource-naming)
- [Naming and tagging conventions tracking template](https://learn.microsoft.com/en-us/azure/cloud-adoption-framework/resources/tools-templates#ready)
- [How to tag your resources on AWS / GCP / Azure?](https://lota.cloud/en/bien-taguer/)


## :books: Videos

[Back To Top](#Table-Of-Contents)

- [Azure Academy](https://www.youtube.com/channel/UC-MXgaFhsYU8PkqgKBdnusQ)

## :books: DashBoards

[Back To Top](#Table-Of-Contents)

- [Azure Orphan Resources workbook](https://techcommunity.microsoft.com/t5/fasttrack-for-azure/azure-orphan-resources/ba-p/3492198)
- [Network Security Dashboard for Microsoft Defender for Cloud](https://github.com/Azure/Microsoft-Defender-for-Cloud/tree/main/Workbooks/Network%20Security%20Dashboard)
- [CCO GitHub Contributions Dashboard](https://github.com/Azure/CCOInsights#cco-github-contributions-dashboard) :fire:
- [CCO ADO Contributions Dashboard](https://github.com/Azure/CCOInsights#cco-ado-contributions-dashboard)
- [Azure Hybrid Benefit Workbook](https://github.com/arthurclares/AzureHybridBenefitWorkbook)
- [AKS Security Workbook](https://techcommunity.microsoft.com/t5/microsoft-sentinel-blog/new-azure-kubernetes-service-aks-security-workbook/ba-p/1867134)
- [Azure Hybrid Benefits Workbook](https://techcommunity.microsoft.com/t5/healthcare-and-life-sciences/tracking-azure-hybrid-benefit-using-azure-workbooks/ba-p/3798857)
- [Azure Saving Plans Dashboard](https://techcommunity.microsoft.com/t5/core-infrastructure-and-security/azure-savings-dashboard/ba-p/3816131)
- [Azure Cost Management Dashboard](https://github.com/sairashaik6677/azure-costmanagement-dashboard)
- [Cloud Roles and Operations Management DashBoard](https://github.com/Azure/cloud-rolesandops)
- [Azure Service Retirement Workbook](https://learn.microsoft.com/en-us/azure/advisor/advisor-how-to-plan-migration-workloads-service-retirement)


## :octocat: GitHub

[Back To Top](#Table-Of-Contents)

- [GitHub emoji cheat sheet](https://github.com/ikatyang/emoji-cheat-sheet/blob/master/README.md) :fire:
- [Build your own octocat](https://myoctocat.com/build-your-octocat/)
- [Bitmoji](https://www.bitmoji.com/stickers/)

## :black_nib: Visio stencils ans icons

[Back To Top](#Table-Of-Contents)

- [Official Microsoft Azure Cloud and AI Symbol / Icon Set - SVG - Pointer](https://www.microsoft.com/en-us/download/details.aspx?id=41937)
- [sandroasp Icon Set](https://github.com/sandroasp/Microsoft-Integration-and-Azure-Stencils-Pack-for-Visio/tree/master/Azure)
- [David-Summers Icon Set](https://github.com/David-Summers/Azure-Design) :fire:
- [Azure Docs collection](http://code.benco.io/icon-collection/azure-docs/)
- [Azure Icons collection](http://code.benco.io/icon-collection/azure-icons/) :fire:
- [Azure Patterns collection](http://code.benco.io/icon-collection/azure-patterns/)
- [Azure cds Collection](http://code.benco.io/icon-collection/azure-cds/)
- [ContentCollateral](https://github.com/mrpaulandrew/ContentCollateral)
- [Azure Icons Libraries for Diagrams.net (Draw.io)](https://pacodelacruz.io/azure-icons-library-diagrams-net) :fire:
- [Azure architecture SVG icons](https://learn.microsoft.com/en-us/azure/architecture/icons/) :fire:

## :page_with_curl: Tips and tricks

[Back To Top](#Table-Of-Contents)

- [Azure Tips and Tricks](https://microsoft.github.io/AzureTipsAndTricks/)
- [Azure Cloud Shell Web](https://shell.azure.com/)

## :statue_of_liberty: LightHouse

[Back To Top](#Table-Of-Contents)

- [Securing Azure Lighthouse with Azure Policy and PIM](https://securecloud.blog/2020/11/13/securing-azure-lighthouse-with-azure-policy-and-azure-privileged-identity-management-for-msps-and-customers/)


## :police_car: Compliance

[Back To Top](#Table-Of-Contents)

- [Microsoft compliance offerings](https://docs.microsoft.com/en-us/compliance/regulatory/offering-home?view=o365-worldwide)
- [Microsoft Privacy Statement](https://privacy.microsoft.com/en-us/privacystatement)
- [Microsoft trust center](https://www.microsoft.com/en-us/trust-center)
- [Service trust portal](https://servicetrust.microsoft.com/)
- [Compliance Manager portal](https://servicetrust.microsoft.com/ComplianceManager/V3#)

## :computer: Virtual machines

[Back To Top](#Table-Of-Contents)

- [Azure VM sizes](https://docs.microsoft.com/en-us/azure/virtual-machines/sizes-general)
- [Start / Stop VMs 1](https://automys.com/library/asset/scheduled-virtual-machine-shutdown-startup-microsoft-azure)
- [*Start / Stop VMs 2](https://github.com/tomasrudh/AutoShutdownSchedule#automation-account-configuration)
- [Azureprice](https://azureprice.net/)
- [Virtual machines selector](https://azure.microsoft.com/en-us/pricing/vm-selector/) :fire:

## :arrow_upper_right: Virtual Machines Scale Set (VMSS)

[Back To Top](#Table-Of-Contents)

- [vmssdashboard](https://github.com/gbowerman/vmssdashboard)
- [asciivmssdashboard](https://github.com/msleal/asciivmssdashboard)

## :a: ARM

[Back To Top](#Table-Of-Contents)

- [Azure Quickstart Templates](https://azure.microsoft.com/en-us/resources/templates/)
- [ARMViz](http://armviz.io)
- [Azure resource explorer](https://resources.azure.com/)
- [Rest API Browser](https://docs.microsoft.com/en-us/rest/api/?view=Azure) :fire:

## :stopwatch: Analytics and monitoring

[Back To Top](#Table-Of-Contents)

- [Log Analytics Query Portal](https://portal.loganalytics.io/demo#/query/main)
- [Kusto explorer](https://docs.microsoft.com/en-us/azure/data-explorer/kusto/tools/kusto-explorer)
- [Monitoring Azure by using Grafana dashboards](https://devblogs.microsoft.com/devops/monitoring-azure-by-using-grafana-dashboards/)
- [Azure Monitor Community](https://github.com/microsoft/AzureMonitorCommunity) :fire:
- [Log Analytics cost](https://trstringer.com/log-analytics-expensive-part-1-discovery/)
- [azure-monitoring-certificates](https://blog.smartcloudarchitect.fr/azure-monitoring-certificates)

## :ninja: Security

[Back To Top](#Table-Of-Contents)

- [Azucar](https://github.com/nccgroup/azucar)
- [ScoutSuite](https://github.com/nccgroup/ScoutSuite)
- [Secure DevOps Kit](https://github.com/azsk/DevOpsKit-docs)
- [Skyark](https://github.com/cyberark/SkyArk)
- [MicroBurst](https://github.com/NetSPI/MicroBurst)
- [Stormspotter](https://github.com/Azure/Stormspotter)
- [Cloud Katana](https://github.com/Azure/Cloud-Katana)
- [Azure Security Control Mappings to MITRE ATT&CK®](https://center-for-threat-informed-defense.github.io/security-stack-mappings/Azure/README.html)
- [Azure Hunter](https://github.com/darkquasar/AzureHunter)
- [Microsoft Security Response Center (MSRC)](https://msrc.microsoft.com/update-guide/vulnerability)
- [Azure Review CheckList](https://github.com/Azure/review-checklists)
- [CloudSploit Security Remediation Guides](https://github.com/aquasecurity/cloud-security-remediation-guides)
- [Identifying & Exploiting Leaked Azure Storage Keys](https://notsosecure.com/identifying-exploiting-leaked-azure-storage-keys)
- [cloud security vulnerabilities](https://github.com/hashishrajan/cloud-security-vulnerabilities)
- [Windows AppLocker Bypass] regsvr32.exe /s /u /i:test.sct scrobj.dll
- [Cybersecurity-jobs-skills-workshop](https://github.com/microsoft/Cybersecurity-jobs-skills-workshop)
- [HackTricks](https://book.hacktricks.xyz/welcome/readme)


## :technologist: Terraform

[Back To Top](#Table-Of-Contents)

- [aztfy](https://github.com/Azure/aztfy)
- [Azure terraform-azurerm-caf-enterprise-scale](https://github.com/Azure/terraform-azurerm-caf-enterprise-scale/wiki)
- [Azure caf-terraform-landingzones](https://github.com/azure/caf-terraform-landingzones)
- [Terraform from 0 to hero flaviusdinu](https://techblog.flaviusdinu.com/terraform-from-0-to-hero-0-i-like-to-start-counting-from-0-maybe-i-enjoy-lists-too-much-72cd0b86ebcd
)
- [azure-network-terraform](https://github.com/kaysalawu/azure-network-terraform)
- [Infracost](https://www.infracost.io/)
- [Johan Vanneuville](https://github.com/JohanVanneuville/Azure-Terraform)
- [Terraform and Azure DevOps pipelines](https://build5nines.com/deploy-terraform-using-azure-devops-yaml-pipelines/
)
- [Deploying Azure Hub-Spoke Networking](https://www.jorgebernhardt.com/terraform-azure-vnet-hub-spoke/)


## :muscle: Bicep

[Back To Top](#Table-Of-Contents)

- [Bicep from 0 to hero](https://github.com/rchaganti/bicepbookexamples)

## :earth_africa: Web

[Back To Top](#Table-Of-Contents)

- [Whirl CSS](https://whirl.netlify.app/)
- [jsoncrack](https://jsoncrack.com/)
- [CSS Tree exemple](https://onaircode.com/html-css-tree-view-examples/)

## :globe_with_meridians: Network

[Back To Top](#Table-Of-Contents)

- [Azure Networking Map](https://techcommunity.microsoft.com/t5/azure-networking-blog/the-azure-networking-map/ba-p/3706001)
- [Network-segmentation-cheat-sheet](https://github.com/sergiomarotco/)
- [Azure Network-Security GitHub Repo](https://github.com/Azure/Azure-Network-Security)
- [Azure Networking GitHub Repo](https://github.com/nehalineogi/azure-networking)
- [Azure Ipam](https://github.com/Azure/ipam)
- [Submarine Cable Map](https://www.submarinecablemap.com/)
- [NVA Redundancy](https://nwktimes.blogspot.com/2023/05/azure-nva-redundancy-part-I.html)


## :page_with_curl: KQL Queries

[Back To Top](#Table-Of-Contents)

- [Query collection](https://github.com/globalbao/azure-resource-graph)


## Fun Images

- [Goodtechthings.com](https://www.goodtechthings.com/)