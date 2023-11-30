<h1>Use-an-Azure-AI-Services-Container</h1>h1>
<h2>Description</h2>
Azure AI services streamline developers' access to Microsoft's scalable infrastructure while they concentrate on their code. To offer more control over service infrastructure and data flow, Azure AI APIs can be containerized, enabling deployment on Azure Container Instances, local Docker servers, or Azure Kubernetes Services clusters. Containerized services retain billing connections to Azure but ensure application data isn't transmitted to the backend, empowering organizations with enhanced setup control for authentication, scalability, and customization.
<h2>Languages and Utilities Used</h2>

- <b>Azure<b>
- <b>Visual Code Studio<b>
- <b>Windows 11<b>

<h2>Setup:</h2>


- <b>Launch Visual Code Studio<b>
- <b>Open the palette (SHIFT+CTRL+P)<b>
- <b>Enter https://github.com/MicrosoftLearning/AI-102-AIEngineer and save to a folder<b>
- <b>Open folder and wait to install<b>
- <b>Open Azure and go to Azure AI Services<b>
- <b>Create multi-service account resource group<b>
<p>
<img src="https://i.imgur.com/xtdofhB.png"height="80%" width="80% alt="vpn"/>

-<b>Wait for deployment to finish, then locate Keys and Endpoints<b>
<p>
<img src="https://i.imgur.com/aL3xG1d.png height="80%" width="80% alt="vpn"/>

- <b>Go back to home, search Container Instances and create a resource<b>
<p>
<img src="https://i.imgur.com/VyXBSb4.png"height="80%" width="80% alt="vpn"/>
<img src="https://i.imgur.com/x2LmFzK.png"height="80%" width="80% alt="vpn"/>

- <b>Enviornmental Variables:<b>
<p>
<img src="https://i.imgur.com/wdtOVz1.png"height="80%" width="80% alt="vpn"/>

-<b>Deploy then go to Overview<b>
-<b>Go to Visual Studio Code and click on the O4-containers folder<b>
-<b>Type rest-test.cmd<b>
-<b>Replace either IP address or FQDN with ones from the Container and save<b>
<p>
<img src="https://i.imgur.com/ppFpDOG.png"height="80%" width="80% alt="vpn"/>
