## L2   Practice-1： 第 1 关	探索书生大模型能力边界


    ### P1-1:  书生大模型全链路开源开放体系历史	
  
  ![连接](./assets/L2/intern_intro_history.jpg)
    
    
    ### P1-2:  书生大模型全链路开源开放体系

  ![连接](./assets/L2/intern_intro_sys.jpg)
  
  
    ###  P1-3: 书生大模型全链路开源开放体系--预训练InterEvo
  
  ![连接](./assets/L2/intern_intro_sys2.jpg)

    ###  P1-4: 书生大模型全链路开源开放体系--预训练 Xtuner
  
  ![连接](./assets/L2/intern_intro_sys3.jpg)

      ###  P1-5: 书生大模型全链路开源开放体系--部署LMDeploy
  
  ![连接](./assets/L2/intern_intro_sys4.jpg)

        ###  P1-6: 书生大模型全链路开源开放体系--智能体Lagent
  
  ![连接](./assets/L2/intern_intro_sys5.jpg)

      ###  P1-7: 书生大模型全链路开源开放体系--RAG茴香豆
  
  ![连接](./assets/L2/intern_intro_sys6-RAG.jpg)

      ###  P1-8: 书生大模型全链路开源开放体系--评估OpenCompass
  
  ![连接](./assets/L2/intern_intro_sys7-eval.jpg)






## L2 Practice-2： 第 2 关	Lagent：从零搭建你的 Multi-Agent

  
  ### P2-1: 使用 Lagent 复现文档中 “制作一个属于自己的Agent” 

  安装Lagent：

  ![连接](./assets/L2/L2-2-Lagent-1-commandline.jpg)
  
  Lagent启动：

  ![连接](./assets/L2/L2-2-Lagent-1-launch.jpg)
  
  页面显示：

  ![连接](./assets/L2/L2-2-Lagent-1-demo1.jpg)


  不选择plugin问问题会报错：

  ![连接](./assets/L2/L2-2-Lagent-1-demo1-error.jpg)
  
  Lagent启动ArxivSearch插件：

  ![连接](./assets/L2/L2-2-Lagent-1-demo1-result.jpg)

  Lagent启动ArxivSearch插件--询问另一个问题：

  ![连接](./assets/L2/L2-2-Lagent-1-demo1-result2.jpg)
  
  创建自己的Agent -- 和风天气的 API 服务：

  ![连接](./assets/L2/L2-2-Lagent-1-weather.jpg)

  创建自己的Agent -- 和风天气创建项目：

  ![连接](./assets/L2/L2-2-Lagent-1-weather2.jpg)


  创建自己的Agent -- 不启动weather插件并询问实时天气：

  ![连接](./assets/L2/L2-2-Lagent-1-demo2-querytheweather-wrong.jpg)


  创建自己的Agent -- 启动weather插件并询问实时天气：

  ![连接](./assets/L2/L2-2-Lagent-1-demo2-querytheweather.jpg)

  创建自己的Agent -- 开启ArxivSearch和weather2个插件并询问：

  ![连接](./assets/L2/L2-2-Lagent-1-demo2-2plugin.jpg)

  ![连接](./assets/L2/L2-2-Lagent-1-demo2-2plugin-selected.jpg)

  ![连接](./assets/L2/L2-2-Lagent-1-demo2-2plugin-multiquery.jpg)


  ### P2-2: Multi-Agents博客写作系统的搭建

多代理：
  ![连接](./assets/L2/L2-2-Lagent-1-demo3-multiagent-launch.jpg)

多代理第二步：
  ![连接](./assets/L2/L2-2-Lagent-1-demo3-multiagent-step2.jpg)

多代理第三步：
  ![连接](./assets/L2/L2-2-Lagent-1-demo3-multiagent-step3.jpg)

多代理结果：
  ![连接](./assets/L2/L2-2-Lagent-1-demo3-multiagent-finalresult.jpg)


  ### P2-3: Lagent上传hf

创建app.py：


  ![连接](./assets/L2/L2-2-Lagent-3-huggingface-app.jpg)

创建requirement.txt：


  ![连接](./assets/L2/L2-2-Lagent-3-huggingface-updaterequirementtext.jpg)

创建hf spaces：


  ![连接](./assets/L2/L2-2-Lagent-3-huggingface-createHFSpaces.jpg)

添加secret：


  ![连接](./assets/L2/L2-2-Lagent-3-huggingface-createHFSpaces-setsecret.jpg)

成功运行应用：

  ![连接](./assets/L2/L2-2-Lagent-3-huggingface-done.jpg)

## L2 Practice-3： 第 3 关  LMDeploy 量化部署进阶实践	


  ### P3-1任务1: LMDeploy环境

  环境部署成功后对话创建一个故事：

  ![连接](./assets/L2/L2-3-LMDeploy-Story.jpg)
  
 环境部署成功后对话创建一个故事时的GPU显存使用量：
  
  ![连接](./assets/L2/L2-3-LMDeploy-GPU-1.jpg)

 环境部署成功后对话创建一个故事时的GPU显存使用量--nvidia-smi：
  
  ![连接](./assets/L2/L2-3-LMDeploy-GPU-nvidia-smi.jpg)

 环境部署成功后对话创建一个故事时的GPU显存使用量-studio-smi：
  
  ![连接](./assets/L2/L2-3-LMDeploy-GPU-studiosmi.jpg)

  ### P3-2任务2: LMDeploy与InternLM2.5
  
  启动API服务器，部署InternLM2.5模型：
  ![连接](./assets/L2/L2-3-LMDeploy-api-launch.jpg)

  fastapi页面启动：
  ![连接](./assets/L2/L2-3-LMDeploy-api-fastapi.jpg)

  其GPU内存使用：
  ![连接](./assets/L2/L2-3-LMDeploy-api-gpu.jpg)

 API对话启用：
   ![连接](./assets/L2/L2-3-LMDeploy-api-story.jpg)

 以Gradio网页形式连接API服务器：
   ![连接](./assets/L2/L2-3-LMDeploy-api-gradio.jpg)

 以Gradio网页形式连接API服务器 --Gradio页面：
   ![连接](./assets/L2/L2-3-LMDeploy-api-gradioweb.jpg)


设置最大kv cache缓存大小 --cache-max-entry-count参数

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-cachemax.jpg)


设置最大kv cache缓存大小 ----cache-max-entry-count 0.4 减少4G显卡内存

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-gpu-reduce.jpg)


设置在线 kv cache int4/int8 量化 -- quant_policy=4

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4Launching.jpg)

设置在线 kv cache int4/int8 量化 -- quant_policy=4 显卡内存

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-GPU.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --开始量化

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-TerminalOutput.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --量化完成 --大约1小时+

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-1.8-Quanting.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --量化后文件大小

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-files.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --原始模型的文件大小

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-files-2.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --原始显卡内存大小

   ![连接](./assets/L2/L2-3-LMDeploy-GPU-1.jpg)   

设置在线 kv cache int4 -- 1.8B模型进行量化 --优化后显卡内存大小

   ![连接](./assets/L2/L2-3-LMDeploy-Quant-Policy4-gpu-reduce.jpg)   

W4A16 量化+ KV cache+KV cache 量化

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16.jpg)

W4A16 量化+ KV cache+KV cache 量化--显卡内存使用：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-2.jpg)


### P3-3 任务3: LMDeploy与InternVL2

针对InternVL系列模型执行模型的量化工作--大概需要12小时--每个layer大概需要14分钟：
此步骤安装flashAttention后每步骤大概需要12分钟

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-InternVLM2.jpg)


针对InternVL系列模型执行模型的量化工作--CPU和内存资源使用：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-InternVLM2-resource.jpg)



针对InternVL系列模型执行模型的量化工作--完成时Terminal输出：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-InternVLM2-done-terminal.jpg)

针对InternVL系列模型执行模型的量化工作--weight packed：
  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-InternVLM2-weight-packed.jpg)

针对InternVL系列模型执行模型的量化工作--完成后文件：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-InternVLM2-file.jpg)


### P3-4 任务4: LMDeploy之FastAPI与Function call

LMDeploy之FastAPI：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-APIDev.jpg)

LMDeploy之FastAPI --第一个Terminal输出：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-APIDev-1stTerminal.jpg)


LMDeploy之FastAPI --funciton_call：

  ![连接](./assets/L2/L2-3-LMDeploy-Quant-W4A16-funcall.jpg)

## L2 Practice-4： 第 4 关	InternVL 多模态模型部署微调实践


  ### P4-1: LMDeploy搭建InternVL2-2B

LMDeploy搭建InternVL2-2B：

  ![连接](./assets/L2/L2-4-InternVL-commandline.jpg)

InternVL2-2B页面：

  ![连接](./assets/L2/L2-4-InternVL-LMDeploy.jpg)

InternVL2-2B启动时GPU显存的使用量：

  ![连接](./assets/L2/L2-4-InternVL-GPU.jpg)


### P4-2: XTuner微调InternVL2-2B实践

 微调终端显示：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-commandline.jpg)

微调时GPU的显卡使用量：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-GPU.jpg)

微调时CPU和内存使用量：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-GPU-source.jpg)

微调完成：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-done.jpg)

微调结果：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-launchafterFT.jpg)

微调后启动网页应用：

  ![连接](./assets/L2/L2-4-InternVL-fineturn-result.jpg)


### P4-3: 上传XTuner微调后的InternVL2-2B模型到ModelScope

 微调InternVL2-2B模型：

  ![连接](./assets/L2/L2-4-InternVL-ModelScope-SFT.png)

 转换模型：

  ![连接](./assets/L2/L2-4-InternVL-ModelScope-convert.png)

本地文件：

  ![连接](./assets/L2/L2-4-InternVL-ModelScope-localfiles.png)


上传到ModelScope后的文件清单：

  ![连接](./assets/L2/L2-4-InternVL-ModelScope-ModelScopefiles.png)


  
## L2 Practice-5： 第 5 关	茴香豆：企业级知识库问答工具

  ### 本节无闯关任务，不作为进阶闯关的要求～





  ## L2 Practice-6： 第 6 关	MindSearch深度解析及实践

  ### P6: 在官方的MindSearch页面 复制Spaces应用到自己的Spaces下，并在必要的步骤以及成功的对话测试结果

  复制后运行：

  ![连接](./assets/L2/L2-6-MindSearch-HuggingFaceSpaces.jpg)

  运行遇到问题log输出：
  ![连接](./assets/L2/L2-6-MindSearch-HuggingFaceSpaces-errorlog.jpg)

  运行遇到问题界面：
  ![连接](./assets/L2/L2-6-MindSearch-HuggingFaceSpaces-error.jpg)

  重启Spaces修复问题：
  ![连接](./assets/L2/L2-6-MindSearch-HuggingFaceSpaces-restarting.jpg)

  正确结果展示：

  ![连接](./assets/L2/L2-6-MindSearch-HuggingFaceSpaces-answer.jpg)

  