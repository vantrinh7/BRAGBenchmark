This study investigates the cooperative binding of oxygen to hemoglobin, focusing on the application of the Hill and Adair equations to model oxygen-hemoglobin interactions. Protein-ligand binding is a foundational concept in biochemistry with critical implications for human physiology. Deepening our understanding of these oxygen binding mechanisms supports the advancement and optimization of biomedical applications and therapeutic interventions for respiratory and cardiovascular diseases.

This repository contains data for a sample task and the analysis of responses from several current frontier models.

* Sample task and solution: the model needs to comprehend a biphasic oxygen hemoglobin binding curve, transform linear axes to log axes of the graph, apply the correct linearized form of the Hill equation, and calculate the final values of the partial pressures of oxygen at half saturation for hemoglobin and myoglobin.
  
* Oxygen-hemoglobin binding data: The first sheet contains the raw data points of partial pressure of oxygen pO<sub>2</sub> and oxygen saturation Y/1-Y for wild-type hemoglobin (Hb), myoglobin (Mb), recombinant hemoglobin (rHb), and hemoglobin treated with inositol hexaphosphate. The second sheet contains a plot of pO<sub>2</sub> versus Y/1-Y with each data point labeled with exact x and y coordinates. The third sheet contains plots before and after the transformation of linear axes into logarithmic axes. 

* Analysis of responses from current frontier models (Gemini, Claude, ChatGPT):


This sample task is difficult for multiple reasons. <br>
* The problem requires advanced understanding of biochemical concepts such as cooperative binding and the application of the Hill equation, on which the model has yet to receive sufficient training. It may struggle to understand what to do to solve the problem. <br>
* There are multiple versions of the Hill equation. The model needs to select the correct version among very closely related and easily confused versions. <br> 
* There are multiple steps to reach the solution. Models can struggle when there are multiple steps to the final answer: look up, then derive; filter, then compare; read, then apply a rule.  <br>
(d)	In this task, a helpful first step to solve the problem is transforming linear axes into log axes, which the model may struggle to do.

My expertise are in the following. <br>
* Basic science knowledge. Protein binding is a major topic in biochemistry. With a bachelor’s degree in biochemistry, I can provide expertise in questions that command the use of textbook biochemistry knowledge. <br>
* Research-backed judgement. With multiple years of research, wet lab work, and co-authored publications, I have expertise in synthesizing scientific studies and providing sound judgement based on high-quality peer-reviewed publications. <br>
* Teaching experience. With previous experience in teaching humans and training AI, I can identify knowledge gaps and provide guidance on filling those gaps. For example, a frontier model may output a wrong solution due to misunderstanding the plot, oversimplifying the problem, and using the wrong equation. I can use techniques such as Chain-of-Thought prompting to show the model how to solve the problem step-by-step. <br>
