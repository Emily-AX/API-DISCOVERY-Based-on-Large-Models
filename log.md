### 工作日志
**2025/2/7**  
1.成功调用了星火大模型API  
（Spark Lite - 无限使用）  
（Spark4.0 Ultra -  2000000 tokens）  
代码文件 ../LLM_Spark.py
网址 https://www.xfyun.cn/    
接口文档 https://www.xfyun.cn/doc/spark/HTTP%E8%B0%83%E7%94%A8%E6%96%87%E6%A1%A3.html#_1-%E6%8E%A5%E5%8F%A3%E8%AF%B4%E6%98%8E  
**2025/2/8**  
1.开始安装Meta Llama模型
操作文档 https://www.llama.com/docs/llama-everywhere/running-meta-llama-on-windows/  
2.主要步骤：     
01：注册Hugging Face，并申请模型访问权限，生成个人登录token  
02：在控制台安装Hugging Face-Hub并登录，开始下载Llama模型 （进行中 6%）
控制台命令如下：  
>huggingface-cli login  #登录  
>tokens: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

>huggingface-cli download meta-llama/Llama-2-7b --local-dir meta-llama/Llama-2-7b #下载  

03：安装 transformer（4.48.3）  accelerate  torch（进行中）  
04：运行脚本 LLM_Llama.py  
**2025/2/9**  
1.成功安装Meta Llama 3-8b 与 torch  
**2025/2/10**  
1.对Spark进行微调，并且完善输出格式  
2.利用GPT-4对50条RapidAPI进行推荐测试  
3.本地运行llama-3-8b时，内存以及显存不足，后续考虑更换轻量级模型 llama-2    
**2025/2/11**  
1.尝试下载llama-2后发现内存依然不足以支持运行，后续考虑在ollama平台上运行大模型。  
**2025/2/14**  
1.成功安装ollama  
2.成功安装llama3.2:1b 和 deepseek-r1:7b  
3.构建了实际使用场景数据  
**2015/2/14**  
1.成功安装bert  
2.正在安装llama模型  
3.准备安装openai提供的api调用  
**2025/2/16**  
1.正在安装llama2.7b.  
2.成功完成传统方法中的基于信息检索的方法并进行了初步实现  
3.准备安装llama3.2.1b和deepseek-r1  
4.正准备实现传统方法中的小规模网络的方法  
**2025/2/17**  
1.完成实现传统方法的小规模网络算法  
2.正在安装llama3.2.1b和deepseek-r1  
3.成功安装llama2.7b  


