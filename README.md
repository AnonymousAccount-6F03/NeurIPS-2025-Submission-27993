# Visualizations for ICML-Submission-16380

We demonstrate the performance of reinforcement learning-based intelligent navigation algorithms in various environments on this page. Through visual analysis of navigation trajectories, we can more intuitively understand the advantages and disadvantages of the algorithm, and provide a basis for further improvement.

In the visualization results, the left side displays the target image, the center shows the first-person perspective observation from the navigation agent, and the right side presents a top-down view of the scene layout, where gray areas indicate traversable regions, arrows denote the agent's position and orientation, and the navigation trajectory is illustrated by blue curves.

The visualization results below demonstrate that our method, through the introduction of distance constraints and similarity constraints, effectively enhances the navigation performance of the agent, resulting in higher SPL values overall. Benefiting from the distance constraints, our agent exhibits significantly fewer collisions with obstacles and environmental elements. Additionally, owing to the similarity constraints, our agent can more efficiently reach the destination once the target appears within its field of view. These findings substantiate the efficacy of our approach, with the visualization outcomes aligning consistently with the quantitative results presented in the paper.

## DiscNav (Ours)

<p>On Gibson</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/d91dad38-5182-4cbc-a71c-d4b0ec847245"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/cdaba847-e717-431f-94c9-1192222d291b"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/58253199-5377-4431-8f4a-176d8e0a8176"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/4c891f5c-3c99-4b58-ae2f-c4c1a1029fbc"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/0dc86885-bda3-44d0-931d-e63e7856c08e"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/5acc5c12-6f6a-48d7-a261-886ecf2968a4"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/007d6bc7-2eda-472d-a7b7-af8a63ec2756"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/819f0f1b-6d6f-4386-9057-0404d36133d6"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/216b35c4-0de8-46f7-a633-5f4b25b578b9"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/2295bf64-b739-4f1c-98f3-b8db6019ab5a"></video>

<p>On HM3D</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/26027895-cadd-4b7b-9f49-0b1f1b4ca172"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/0dbc80b9-5c50-4000-a83a-b447dced7a60"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/8b27fc19-7060-4215-b447-9c8bfd97bbe2"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/f64018a2-c4ea-4c2a-ac87-1cb9622f2625"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/ea1cefe5-4d16-4ddd-8ef5-db7405b4b6d3"></video>

<p>On MP3D</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/73308315-435a-4729-a749-f42cbb98c2de"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/da3f5243-ab12-4788-9050-055c5852574c"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/6f15597b-af42-46c6-9aec-2b8c89d0ec61"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/9e58515d-ea5a-4d7f-ac8f-3c6b8b3255ab"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/a6dafad3-3e24-49c8-b029-4efa3abf2f1f"></video>

## Comparison Methods

<p>MemAug (MEZGHAN ET AL., 2022)</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/8fafb522-df45-438d-8246-5dd191233376"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/2b810736-9989-413c-8835-9b92bb059f0d"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/95783530-e8d2-4071-b25e-d46f15c69c55"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/72f49eb7-3a6b-4717-b6db-70df1b45d55a"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/9614c2e4-2684-4198-968b-0f2b70051fe0"></video>

<p>ZER (AL-HALAH ET AL., 2022)</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/07fdae67-dfb8-41c0-b53e-8bc6a9332e04"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/208248a4-bfbe-4705-b9b4-0ab267e915c8"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/1275c034-4a57-4c35-818e-47d32f2d003c"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/6fdeba22-b452-4524-9b96-135bce55381e"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/9c681d7b-5596-4d74-bd06-5aa9a55353ee"></video>

<p>TSGM (KIM ET AL., 2023)</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/5d783a77-cc57-4c5a-b362-6414b242c95f"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/030d7abb-425e-4f5c-ae23-6dd4a57b8533"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/2e8a19ae-86d3-476f-bd6d-3dc9649691ae"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/4f47d2e4-1c8a-464d-b92f-dcfdfd1f9854"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/5c888334-063c-4a33-ac3b-8dcfb3a6d101"></video>

## Failure Cases

<p>Some failure cases</p>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/36fa9439-a5a7-4f44-ac14-0726f0e614c5"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/4d0643d0-512f-4578-a3ab-2a5cae3b1cbf"></video>
<video src="https://github.com/AnonymousAccount-6F03/ICML-Visualizations-16380/assets/b4e68484-d4d3-4a2f-9ff3-6fa5a2c4f7d4"></video>
