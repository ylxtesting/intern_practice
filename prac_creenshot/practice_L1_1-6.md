## L1   Practice-1： 第 1 关	书生大模型全链路开源体系	



    ### P1-1:  书生大模型全链路开源开放体系历史	
  
  ![连接](./assets/L1/intern_intro_history.jpg)
    
    
    ### P1-2:  书生大模型全链路开源开放体系

  ![连接](./assets/L1/intern_intro_sys.jpg)
  
  
    ###  P1-3: 书生大模型全链路开源开放体系--预训练InterEvo
  
  ![连接](./assets/L1/intern_intro_sys2.jpg)

    ###  P1-4: 书生大模型全链路开源开放体系--预训练 Xtuner
  
  ![连接](./assets/L1/intern_intro_sys3.jpg)

      ###  P1-5: 书生大模型全链路开源开放体系--部署LMDeploy
  
  ![连接](./assets/L1/intern_intro_sys4.jpg)

        ###  P1-6: 书生大模型全链路开源开放体系--智能体Lagent
  
  ![连接](./assets/L1/intern_intro_sys5.jpg)

      ###  P1-7: 书生大模型全链路开源开放体系--RAG茴香豆
  
  ![连接](./assets/L1/intern_intro_sys6-RAG.jpg)

      ###  P1-8: 书生大模型全链路开源开放体系--评估OpenCompass
  
  ![连接](./assets/L1/intern_intro_sys7-eval.jpg)






## L1 Practice-2： 第 2 关	玩转书生「多模态对话」和「AI搜索」产品


  
  ### P2-1: 玩转书生和「AI搜索」产品

  MindSearch问题1：

  ![连接](./assets/L1/Q1-1.jpg)
  
  MindSearch问题2：

  ![连接](./assets/L1/Q1-2.jpg)
  
  MindSearch问题3：

  ![连接](./assets/L1/Q1-3.jpg)

  ### P2-1: 玩转书生.浦语

  ![连接](./assets/L1/Q2-1.jpg)

  ### P3-1: 玩转书生「多模态对话」

  ![连接](./assets/L1/Q3-1.jpg)


## L1 Practice-3： 第 3 关	浦语提示词工程实践	


  ### P3-1任务1: 引导语言模型正确回答出“strawberry”中有几个字母“r”

  
  ![连接](./assets/L1/Prompt-3r.jpg)
  

  

  ### P3-2任务2: 进阶：剧本创作助手
  
  添加提示词前：
  ![连接](./assets/L1/juben-1.jpg)

  添加如下提示词：
  ![连接](./assets/L1/juben-prompt.jpg)

  添加提示词后最终结果：
   ![连接](./assets/L1/juben-2-addingprompt.jpg)



### P3-3 任务3: 进阶：科幻小说生成

更新prompts：

  ![连接](./assets/L1/book-1.jpg)

开始创作：

  ![连接](./assets/L1/book-2.jpg)

创作结果：

  ![连接](./assets/L1/book-3.jpg)

中途第12章出现英文：
  ![连接](./assets/L1/book-4.jpg)

生产md文件
  ![连接](./assets/L1/book-5.jpg)




## L1 Practice-4： 第 4 关	InternLM + LlamaIndex RAG 实践	


  ### P4-1: 基于 LlamaIndex 构建自己的 RAG 知识库，借助 LlamaIndex 后浦语 API 具备回答 A 的能力

RAG 知识库构建前API：

  ![连接](./assets/L1/llamaIndexapi_before-rag.jpg)

RAG 知识库构建后API：

  ![连接](./assets/L1/llamaIndexapi_after-rag.jpg)

 



  ### P4-2: 基于 LlamaIndex 构建自己的 RAG 知识库， LlamaIndex 后 InternLM2-Chat-1.8B 模型具备回答 A 的能力

  RAG 知识库构建前本地模型：

  ![连接](./assets/L1/llamaIndexlocal_streamlit-1.jpg)

RAG 知识库构建后本地模型：

  ![连接](./assets/L1/llamaIndexlocal_streamlit-2.jpg)


  ### P4-3: 基于 LlamaIndex和浦语API部署到HF

  创建app.py：

  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-apppy.jpg)
  

  更新app.py,使用hf上的sentence model，同时更新data目录：

  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-updatingapp.jpg)

  这两行代码更新为：


  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-updatingapp-updated.jpg)

  创建requirement.txt

  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-requimenttxt.jpg)
  

  上传到hf，然后开始自动构建：


  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-building.jpg)




  成功运行：



  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-running.jpg)

  
  
  HF spaces上的文件清单：


  ![连接](./assets/L1/L1-4-LLamaIndexRAG-HF-files.jpg)




  
## L1 Practice-5： 第 6 关	XTuner 微调个人小助手认知

  ### P5-1: 使用 XTuner 微调 InternLM2-Chat-7B 实现自己的小助手认知

开始用XTuner微调：

  ![连接](./assets/L1/xtuner-1.jpg)

XTuner微调中GPU使用情况：
  ![连接](./assets/L1/xtuner-1-gpu.jpg)

XTuner微调后小助手名字更新：

  ![连接](./assets/L1/xtuner-after.jpg)

  ![连接](./assets/L1/xtuner-after2.jpg)


  ![连接](./assets/L1/xtuner-after3.jpg)

  ![连接](./assets/L1/xtuner-after4.jpg)

### P5-2: 上传微调后的模型到ModelScope

用XTuner完成微调：

  ![连接](./assets/L1/L1-5-Xtuner-HF-SFTfile.png)

XTuner微调后的adapter文件：

  ![连接](./assets/L1/L1-5-Xtuner-HF-adapter.png)

合并后的文件：

  ![连接](./assets/L1/L1-5-Xtuner-HF-files.png)  

上传到ModelScope：

  ![连接](./assets/L1/L1-5-Xtuner-HF-ModelScopeWeb.png)  


  ## L1 Practice-6： 第 7 关	OpenCompass 评测书生大模型实践

  ### P4-1: 使用 OpenCompass 评测浦语 API 记录复现过程并截图
    运行前数据准备：

  ![连接](./assets/L1/OpenCompass-1-data.jpg)

  运行评估遇到问题：
  ![连接](./assets/L1/OpenCompass-1-config-error.jpg)

 修复问题：
  ![连接](./assets/L1/OpenCompass-1-config-error-fix.jpg)

  展示config list：

  ![连接](./assets/L1/OpenCompass-1-config.jpg)

  OpenCompass评测中：

  ![连接](./assets/L1/OpenCompass-1-inference-1.jpg)

  展示评测结果：

  ![连接](./assets/L1/OpenCompass-1-result.jpg)


