# R2 + B2 + GitHub + GitLab 方案

1. 把 `worker.js` 复制到 Cloudflare Worker 处，添加账户信息

2. 在 Cloudflare 里建一个 API 用于读取 Worker 里的账户信息

https://dash.cloudflare.com/profile/api-tokens

![image](https://github.com/user-attachments/assets/a80e3083-3eac-42db-acfc-c8f08177870d)
![image](https://github.com/user-attachments/assets/9e49b29a-54ae-46f0-aeda-28d95f4a9041)
![image](https://github.com/user-attachments/assets/11dceb4b-ab2e-41a8-b8e4-7317bcf4b50f)
![image](https://github.com/user-attachments/assets/b1e6f1c3-3d8d-4ba3-8d98-35ab4f061b14)
![image](https://github.com/user-attachments/assets/81e66642-cd5c-43d3-bb72-7fecf24e16a3)
![image](https://github.com/user-attachments/assets/3c832e81-bfc6-480d-939c-1d0731a07c17)

3. 在 Action 处设置 3 个 secret 变量

![image](https://github.com/user-attachments/assets/25b8d0fa-8302-4cb9-a6db-83e449e9664c)