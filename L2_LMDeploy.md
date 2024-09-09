# LMDeploy 量化部署实践闯关任务
## 配置LMDeploy环境
### LMDeploy验证启动模型文件
![image](https://github.com/user-attachments/assets/06a188e1-1722-4c9e-a393-3b5b2db390c3)
50%A100*1 建立机器，同样运行InternLM2.5 7B模型，会发现此时显存占用为36GB。

![image](https://github.com/user-attachments/assets/60f5de20-38f3-424d-97e7-3e445c225436)
显存占用情况

![image](https://github.com/user-attachments/assets/a434aa20-9371-4072-809e-ca52566e864b)
## LMDeploy与InternLM2.5
### LMDeploy API部署InternLM2.5
#### 启动API服务器
![image](https://github.com/user-attachments/assets/695662d3-1bcc-487a-a58d-c54d08c509b8)

#### 以命令行形式连接API服务器
![image](https://github.com/user-attachments/assets/9679f6f5-efb6-41e0-b400-3e499fd98923)

#### 以Gradio网页形式连接API服务器
![image](https://github.com/user-attachments/assets/9ba968dd-790b-4922-b6c2-4cbaa4b72fa4)

### LMDeploy Lite
#### 设置最大kv cache缓存大小
![image](https://github.com/user-attachments/assets/63e452a2-bac0-4684-af98-8a08dcea5a93)
![image](https://github.com/user-attachments/assets/875ba2e8-2bc0-443b-ba14-d4c0a8959b72)

#### 设置在线 kv cache int4/int8 量化
![image](https://github.com/user-attachments/assets/7100e170-573f-4f72-a548-15858e7fed95)
#### W4A16 模型量化和部署
![image](https://github.com/user-attachments/assets/6bb6dcad-b70f-4484-a2a4-38286f245bb3)
![image](https://github.com/user-attachments/assets/3756ea07-6d8b-40fe-a742-9e546978d653)
![image](https://github.com/user-attachments/assets/aabeb670-5e9b-4890-8a98-8a4a4793f34a)
#### W4A16 量化+ KV cache+KV cache 量化
![image](https://github.com/user-attachments/assets/30c8e339-eaa0-46d0-94c6-3bb36d1baf1d)
![image](https://github.com/user-attachments/assets/c00e64c7-53fd-48c8-bf1a-2b8f86c5e334)
## LMDeploy之FastAPI与Function call
### API开发
![image](https://github.com/user-attachments/assets/f585ef65-9a09-4add-a2c7-7b4e9c5cafb4)
![image](https://github.com/user-attachments/assets/76a60ce0-6003-4c6a-a833-b742b8b33c1a)
### Function call
![image](https://github.com/user-attachments/assets/e351b518-5d2d-4749-8695-9d0e040ccf04)
![image](https://github.com/user-attachments/assets/1d828a5f-d974-4eb3-bfea-4454b1f75b3b)
![image](https://github.com/user-attachments/assets/a40bbb6b-5079-44a1-a6b6-1142a299cbe4)





