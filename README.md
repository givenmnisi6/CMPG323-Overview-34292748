# Overview

## Repositories
In my approach to this semester I'm going to use five repositories below:
 <ul>
<li>Project 1 - Agile & Scrum: <a href= "https://github.com/users/givenmnisi6/projects/3"> Kanban Project </a></li>
<li>Project 2 - <a href= "https://github.com/givenmnisi6/CMPG323-Project-2-34292748"> API Development</a></li>
<li>Project 3 - <a href= "https://github.com/givenmnisi6/CMPG323-Project-3-34292748"> Standards & Patterns</a></li>
<li>Project 4 - <a href= "https://github.com/givenmnisi6/CMPG323-Project-4-34292748"> Testing & RPA</a></li>
<li>Project 5 - <a href= "https://github.com/givenmnisi6/CMPG323-Project-5-34292748"> Reporting & Monitoring</a></li>
</ul>


## Context Diagram
<img src="/Images/Context diagram.png" alt="Context Diagram">
Regarding my project I'm going to have each repository for each project if source control is needed. Essentially I'm going to have 5 different repositories and one project where all the of them come together through one "Kanban".

## Branching Strategy

In all of my projects, Branching strategies will be used since I want to avoid conflicts when I am merging them and also allow a much easier integration of changes made into the main trunk. Moreover, to help organize a series of planned, structured releases. A branching strategy that I will be using in all of my projects is GitHub-Flow. Since all of the projects are individually and we have a single release version for each of our projects for each repository, GitHub-Flow is the winner for me. GitHub Flow is a simple and effective way to support continuous deployment and release. It gives me a delivery-focused project as possible.
#### Implementation
Most of my Implementation I will be using branches after major changes I push to my main branch and delete the branch I created. 
<ul>
<li>The main is being branched to the feature branch, then code is added to the feature branch.</li>
<li>A pull request is created and pushed to pre-production while adding things and fixing bugs, when I'm content with the release I merge back to main.</li>
</ul>
This strategy eliminates a lot of room for error, if something goes wrong, I can simply roll back to the previous version.
<ul>
<li>The GitHub Flow branching strategy will consist of the following branches:  </li>
<li>Master (main) - for production purposes </li>
<li>Feature/task - for the development of new features </li>
<li>Hotfix - to assist when there's a bug that has been found and needs fixing in production. A hotfix originates from the master branch and merges back into the master and develops. </li>

</ul>

## .gitignore files
<li>In my API Project, I'll use gitignore to ignore the JSON files anytime I save code in a public repository and want to secure it so that it???s not publicly accessible.</li>
<li>Under my MVC Web Application, I intend to use gitignore to ignore the bin, obj folders and JSON files; I just want the source code in source control. Moreover I will store all the Connection Strings in .JSON file and gitignore them. </li>
<li>In terms of RPA & Testing , I'm going to gitignore files like entities, local, templates, screenshots, settings, tmh</li>
<li>In Reporting project there won't be files that will be ignored.</li>
</ul>

## Storage of Credentials
In terms of storing sensitive credentials:
- I???ll utilize a .JSON file in API Development and Standards & Patterns. 
- In Testing & RPA, credentials will be stored in UiPath Orchestrator.
- In Reporting there will not be credentials that need to be stored.

## Reference List
<ul>
<li><p>Nick Chapsas. (2021, Aug 10).<i> Getting started with branching workflows, Git Flow and GitHub Flow.</i> [Video]. YouTube. https://youtu.be/gW6dFpTMk8s <br></li>
<li><p>Valaxy Technologies. (2020, Oct 6).<i>Branching Strategies on Git | Real-time Git Branching Strategy for a DevOps project</i>. [Video]. YouTube https://youtu.be/Bg8tiOLZw4A <br></li>
<li><p>Adam Marczak. (2020, Oct 21).<i> AZ-900 Episode 27 | Azure Key Vault | Secret, Key and Certificate Management.</i> [Video]. YouTube https://youtu.be/AA3yYg9Zq9w <br></li>
<li><p>Devchild. (2018, Sept 2).<i> The gitflow workflow - in less than 5 mins.</i> [Video]. YouTube https://youtu.be/1SXpE08hvGs <br></li>
<li><p>Rowan Haddad. (2022).<i> What Are the Best Git Branching Strategies.</i> <a href="https://www.flagship.io/git-branching-strategies/">Git Branching Strategies: GitFlow, Github Flow, Trunk Based</a>. Date of access: 08 March 2022.<br></li>
<li><p>David Coulter. (2021).<i> Quickstart: Set and retrieve a secret from Azure Key Vault using the Azure portal. </i><a href="https://docs.microsoft.com/en-us/azure/key-vault/secrets/quick-create-portal">Quickstart: Set and retrieve a secret from Azure Key Vault using the Azure portal</a>. Date of access: 14 Dec. 2021.<br></li>
<li><p>Tara Rosen. (2020).<i> How To Create A .gitignore File To Hide Your API Keys. </i><a href="https://medium.com/@t.rosen2101/how-to-create-a-gitignore-file-to-hide-your-api-keys-95b3e6692e41">How To Create A .gitignore File To Hide Your API Keys</a>. Date of access: 20 Mar. 2020
<li><p>Quang Nguyen. (2021). <i>Git-Flow vs GitHub-Flow.</i> Git-Flow vs GitHub-Flow. <a href="https://quangnguyennd.medium.com/git-flow-vs-github-flow-620c922b2cbd">Git vs GitHub pros and cons. continuous??? | by Quang Nguyen | Medium</a>. Date of access: 10 Sep 2021.<br></li> 
<li><p>CodeWall. (2019). <i>A Git-Flow Explainer & How To Tutorial.</i><a href="https://www.codewall.co.uk/a-git-flow-explainer-how-to-tutorial/">A Git-Flow Explainer & How To Tutorial - Code Wall</a>. Date of access: 30 May 2019.<br></li> 
<li><p>Zhou, W., Li, L., Luo, M. and Chou, W., 2014, May. REST API design patterns for SDN northbound API. <i> In 2014 28th international conference on advanced information networking and applications workshops </i> (pp. 358-365). IEEE.<br></li> 
<li><p>Sohan, S.M., Maurer, F., Anslow, C. and Robillard, M.P., 2017, October. A study of the effectiveness of usage examples in REST API documentation.<i> In 2017 IEEE Symposium on Visual Languages and Human-Centric Computing (VL/HCC)</i>(pp. 53-61). IEEE.<br></li> 
<li><p>Masse, M., 2011.<i> REST API design rulebook: designing consistent RESTful web service interfaces </i>. " O'Reilly Media, Inc."<br></li> 
<li><p>Chadwick, J., Snyder, T. and Panda, H., 2012. <i>Programming ASP. NET MVC 4: Developing Real-World Web Applications with ASP. NET MVC</i>. " O'Reilly Media, Inc."<br></li> 
<li><p>Soni, A. and Ranga, V., 2019. API features individualizing of web services: REST and SOAP.<i>International Journal of Innovative Technology and Exploring Engineering </i>, 8(9), pp.664-671.<br></li> 
<li><p>Mumbaikar, S. and Padiya, P., 2013. Web services based on soap and rest principles.<i> International Journal of Scientific and Research Publications, 3</i>(5), pp.1-4.<br></li> 
<li><p>Halili, F. and Ramadani, E., 2018. Web services: a comparison of soap and rest services. <i>Modern Applied Science, 12</i>(3), p.175.<br></li> 
<li><p>De, B., 2017. API documentation. <i>In API Management </i>(pp. 59-80). Apress, Berkeley, CA.<br></li> 
<li><p>Haunts, S., 2019. Key Storage and Azure Key Vault.<i> In Applied Cryptography in. NET and Azure Key Vault </i>(pp. 143-168). Apress, Berkeley, CA.<br></li> 
<li><p>Herath, P., 2022. Working with Azure Key Vault. <i>In Azure Cloud Security for Absolute Beginners</i> (pp. 71-91). Apress, Berkeley, CA.<br></li> 
<li><p>MuleSoft Videos. (2015, Jun 20). <i> What is an API?</i>. [Video]. YouTube https://youtu.be/s7wmiS2mSXY <br></li>
<li><p>Simply Explained. (2019, Nov 12).<i> What Are APIs? ??? Simply Explained</i>. [Video]. YouTube https://youtu.be/OVvTv9Hy91Q <br></li>
<li><p>Imperva. (2019, Nov 16).<i> API Security Explained</i>. [Video]. YouTube https://youtu.be/LeVQlxLVD8A<br></li>
<li><p>Nordic APIs. (2019, May 28).<i> 5 Best Practices for Securing Your APIs</i>. [Video]. YouTube https://youtu.be/6wRuKgjbBVU<br></li>
<li><p>Udacity (2016, Jun 6).<i> Token Based Authentication</i>. [Video]. YouTube https://youtu.be/woNZJMSNbuo <br></li>
<li><p>WafaStudies. (2020, Jun 5).<i> Store Secrets in Azure Key Vault using Azure Portal</i>. [Video]. YouTube https://youtu.be/Rb7qz_emvsg<br></li>
<li><p>Paddy Maddy. (2020, Dec 24).<i> Storage Account service Encryption Azure KeyVault secret key encryption</i>. [Video]. YouTube https://youtu.be/N6nNJ_NrbS4<br></li>

<li><p>C. Nienaber & R. Suter. (2022, Mar). <i>ASP.NET Core web API documentation with Swagger / OpenAPI</i>. https://docs.microsoft.com/en-us/aspnet/core/tutorials/web-api-help-pages-using-swagger?view=aspnetcore-3.1 </li>
<li><p> R. Anderson & K. Larkin. (2022, Aug).<i>Tutorial: Create a web API with ASP.NET Core</i>. https://docs.microsoft.com/en-us/aspnet/core/tutorials/first-web-api?view=aspnetcore-6.0&tabs=visual-studio</li>
<li><p>R. Anderson & K. Larkin. (2022, Jul).<i> Configuration in ASP.NET Core</i>. https://docs.microsoft.com/en-us/aspnet/core/fundamentals/configuration/?view=aspnetcore-6.0</li>
<li><p>Sanjay. (2021, Jul).<i> Entity Framework Core in ASP.NET Core 3.1 ??? Getting Started</i>. https://procodeguide.com/programming/entity-framework-core-in-asp-net-core/</li>
<li><p>J. Muller. (2022, Jan). <i>Join two entities in.NET Core, using lambda and Entity Framerwork Core</i>. https://jd-bots.com/2022/01/24/join-two-entities-in-net-core-using-lambda-and-entity-framework-core/</li>
<li><p> M. Soucoup. (2022, Mar). <i> Publish an ASP.NET Core web API to Azure API Management with Visual Studio </i>. https://docs.microsoft.com/en-us/aspnet/core/tutorials/publish-to-azure-api-management-using-vs?view=aspnetcore-6.0</li>
<li><p>Price, M.J., 2019. <i>C# 8.0 and. NET Core 3.0???Modern Cross-Platform Development: Build applications with C#,. NET Core, Entity Framework Core, ASP. NET Core, and ML. NET using Visual Studio Code. Packt Publishing Ltd.</i></li>
<li><p>Chanda, S. and Foggon, D., 2013. <i>Introducing Language-Integrated Query (LINQ)</i>. In Beginning ASP. NET 4.5 Databases (pp. 79-98). Apress, Berkeley, CA.
<li><p> Azure Crash Course. <i>Azure API Management Crash Course.</i> [Video]. YouTube https://youtu.be/3z_XmIrGbsI</li>
<li><p> DEVREAL. <i>Azure API Management in 7 (from provisioning to API deployment) - tutorial for beginners.</i> [Video]. YouTube https://youtu.be/Gu9reN09mXI
<li><p> Microsoft Azure.<i> Azure API Management.</i> [Video]. YouTube https://youtu.be/0yf_xm5cPIo</li></li>
<li><p>Reval Govender. <i>Git Flow Part 1 - What is Git Flow</i>. [Video]. YouTube https://youtu.be/6LhTe8Mz6jM</li>
<li><p> Microsoft (2020). <i> ASP.NET MVC Overview</i>. https://learn.microsoft.com/en-us/aspnet/mvc/overview/older-versions-1/overview/asp-net-mvc-overview  </li>
<li><p> Microsoft. <i> Secure a .NET web app with the ASP.NET Core Identity framework</i>. https://learn.microsoft.com/en-us/training/modules/secure-aspnet-core-identity/ </li>
<li><p> Microsot. <i> Build web apps with ASP.NET Core for beginners. </i> https://learn.microsoft.com/en-us/training/paths/aspnet-core-web-app/ </li>
<li><p> Kanchan Naik (2021, June 17). <i> Design Patterns In C# .NET . </i> https://www.c-sharpcorner.com/UploadFile/bd5be5/design-patterns-in-net/ </li>
<li><p> Manikavelu Velayutham (2012, May 13). <i> Architectural Patterns in .NET. </i> https://www.c-sharpcorner.com/uploadfile/babu_2082/architectural-patterns-in-net/ </li>
<li><p> Microsoft (2022). <i> Design the infrastructure persistence layer</i>. https://learn.microsoft.com/en-us/dotnet/architecture/microservices/microservice-ddd-cqrs-patterns/infrastructure-persistence-layer-design </li>
<li><p> Bergman (2017, 20 April). <i> Repository Design Pattern </i>. https://medium.com/@pererikbergman/repository-design-pattern-e28c0f3e4a30 </li>
<li><p> M. Coetzee & J. Muller. 2022, 8 Sept.<i> Patterns Intro </i>.[Video]. <a href= "https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=07+Cmpg+323+-+Patterns+Intro+Project+2+submission+8+Sept.m4v">Patterns Intro</a></li>
<li><p> M. Coetzee & J. Muller. 2022, 15 Sept.<i> Design Patterns </i>.[Video]. <a href="https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=08+CMPG+323+-+Design+patternc+class+15+Sept.m4v">Design Patterns</a></li>
<li><p> M. Coetzee. 2022, 13 Sept. <i> Best practise and standards </i>.[Video]. <a href="https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=08+CMPG323+-+Project+3+-+Best+practise+and+standards+13+Sept.m4v"> Best practise and standards </a></li>
<li><p> M. Coetzee. 2022, 13 Sept. <i> WebApp demo </i>.[Video]. <a href="https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=08+CMPG323+-+Project+3+-+WebApp+demo+13+Sept.m4v"> WebApp demo </a></li> 
<li><p>M. Coetzee & J. Muller. 2022, 20 Sept.<i> Project 3 repository Pattern concepts</i>. [Video] . <a href="https://www.dropbox.com/sh/p8fiokfpiqv4gud/AAC5X8SdanTnduTWYzVq4kQ7a?dl=0&preview=09+CMPG323+-+Project+3+repository+pattern+concepts+20+Sept+recording.mp4"> Project 3 repository Pattern concepts </a></li>

</ul>
