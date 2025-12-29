# sbyttest1
视频说明详情

输出：
```
print("Hello, World!")
```

nginx配置文件：https://github.com/kzlgithub/sbyttest1/blob/main/code/nginx.conf


# 标题1
## 标题2
### 标题3

[![【免费节点】薅CF羊毛自己搭建免费节点](https://img.youtube.com/vi/tPDiM5gYfeg/0.jpg)](https://www.youtube.com/watch?v=tPDiM5gYfeg)


# 🚀 快速上手：自建免费节点教程

### 📺 视频演示
[![【免费节点】薅CF羊毛自己搭建免费节点](https://img.youtube.com/vi/tPDiM5gYfeg/0.jpg)](https://www.youtube.com/watch?v=tPDiM5gYfeg)

---

### 🛠️ 核心操作步骤

**1. 创建 KV 命名空间** 在 Cloudflare 控制台中点击 `Workers & Pages` -> `KV` -> `Create instance`。

**2. 部署 Worker 代码** 复制视频中提到的代码并填入以下命令（示例）：

```bash
npm install -g wrangler
wrangler publish
```

### nginx.conf:
<details>
<summary>点击展开查看完整代码</summary>

```
{
  "inbounds": [
    {
      "port": 8388, 
      "protocol": "vmess",    
      "settings": {
        "clients": [
          {
            "id": "af41686b-cb85-494a-a554-eeaa1514bca7",  
            "alterId": 0
          }
        ]
      },
      "streamSettings": {
        "network": "tcp",
        "security": "tls",
        "tlsSettings": {
          "certificates": [
            {
              "certificateFile": "/usr/local/etc/v2ray/server.crt", 
              "keyFile": "/usr/local/etc/v2ray/server.key" 
            }
          ]
        }
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "freedom",
      "settings": {}
    }
  ]
}

{
  "inbounds": [
    {
      "port": 8388, 
      "protocol": "vmess",    
      "settings": {
        "clients": [
          {
            "id": "af41686b-cb85-494a-a554-eeaa1514bca7",  
            "alterId": 0
          }
        ]
      },
      "streamSettings": {
        "network": "tcp",
        "security": "tls",
        "tlsSettings": {
          "certificates": [
            {
              "certificateFile": "/usr/local/etc/v2ray/server.crt", 
              "keyFile": "/usr/local/etc/v2ray/server.key" 
            }
          ]
        }
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "freedom",
      "settings": {}
    }
  ]
}

{
  "inbounds": [
    {
      "port": 8388, 
      "protocol": "vmess",    
      "settings": {
        "clients": [
          {
            "id": "af41686b-cb85-494a-a554-eeaa1514bca7",  
            "alterId": 0
          }
        ]
      },
      "streamSettings": {
        "network": "tcp",
        "security": "tls",
        "tlsSettings": {
          "certificates": [
            {
              "certificateFile": "/usr/local/etc/v2ray/server.crt", 
              "keyFile": "/usr/local/etc/v2ray/server.key" 
            }
          ]
        }
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "freedom",
      "settings": {}
    }
  ]
}

{
  "inbounds": [
    {
      "port": 8388, 
      "protocol": "vmess",    
      "settings": {
        "clients": [
          {
            "id": "af41686b-cb85-494a-a554-eeaa1514bca7",  
            "alterId": 0
          }
        ]
      },
      "streamSettings": {
        "network": "tcp",
        "security": "tls",
        "tlsSettings": {
          "certificates": [
            {
              "certificateFile": "/usr/local/etc/v2ray/server.crt", 
              "keyFile": "/usr/local/etc/v2ray/server.key" 
            }
          ]
        }
      }
    }
  ],
  "outbounds": [
    {
      "protocol": "freedom",
      "settings": {}
    }
  ]
}
```
