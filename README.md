# Pattern-Recognition-and-Reconstruction-Detecting-Malicious-Deletions-in-Textual-Communications

Note: this model is implemented with PyTorch as described in our paper:

Solanke, A. A., Chen, X., & Ramírez-Cruz, Y. (2021, December). "Pattern Recognition and Reconstruction: Detecting Malicious Deletions in Textual Communications." In 2021 IEEE International Conference on Big Data (Big Data) (pp. 2574-2582). IEEE

**Abstract:** 
Digital  forensic  artifacts  aim  to  provide  evidencefrom  digital  sources  for  attributing  blame  to  suspects,  assessingtheir intents, corroborating their statements or alibis, etc. Textualdata  is  a  significant  source  of  artifacts,  which  can  take  variousforms,  for  instance  in  the  form  of  communications.  E-mails,memos,  tweets,  and  text  messages  are  all  examples  of  textualcommunications.  Complex  statistical,  linguistic  and  other  scien-tific procedures can be manually applied to this data to uncoversignificant   clues   that   point   the   way   to   factual   information. While  expert   investigators  can   undertake  this   task,  there   is a  possibility  that  critical  information  is  missed  or  overlooked. The  primary  objective  of  this  work  is  to  aid  investigators  bypartially automating the detection of suspicious e-mail deletions. Our approach consists in building a dynamic graph to representthe  temporal  evolution  of  communications,  and  then  using  aVariational Graph Autoencoder to detect possible e-mail deletionsin  this  graph.  Our  model  uses  multiple  types  of  features  for representing node and edge attributes, some of which are basedon  metadata  of  the  messages  and  the  rest  are  extracted  fromthe  contents  using  natural  language  processing  and  text  miningtechniques.  We  use  the  autoencoder  to  detect  missing  edges, which  we  interpret  as  potential  deletions;  and  to  reconstruct their  features,  from  which  we  emit  hypotheses  about  the  topicsof  deleted  messages.  We  conducted  an  empirical  evaluation  ofour  model  on  the  Enron  e-mail  dataset,  which  shows  that  ourmodel  is  able  to  accurately  detect  a  significant  proportion  of missing  communications  and  to  reconstruct  the  correspondingtopic  vectors. Index  Terms—Digital  Forensics,  Variational  Graph  Autoen-coders,  Forensic  Artificial  Intelligence

## Requirements
```
CUDA==10.2
Python==2.7.12
networkx==2.2
scipy==1.1.0
torch==1.6.0          
torch-geometric==1.0.2      
torch-scatter==1.0.2      
torch-sparse==1.0.2  
sklearn

## Cite
Kindly cite this paper if you make any reference to its contents or codes
```
@inproceedings{solanke2021,
  title{Pattern Recognition and Reconstruction: Detecting Malicious Deletions in Textual Communications},
  author={Solanke, Abiodun A. and Chen, Xihui and Ramiréz-Cruz, Yunior},
  booktitle={2021 IEEE International Conference on Big Data (Big Data)},
  pages={2574-2582},
  year={2021} 
  }
```  
