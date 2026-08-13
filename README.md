# BTN_CTRL_OPS

以 Docker Compose 整合核心專案、Cloudflare Tunnel 與 Traefik，打造易於部署與管理的容器化服務架構

## 專案特點

* Button Control Center 的容器化部署架構
* 使用 Docker Compose 管理與拆分各項服務
* 使用 Cloudflare Tunnel 與 Traefik提供對外入口及反向代理
* 應用服務與基礎設施可獨立部署
* 以 Docker Network 隔離內外部服務
* 支援環境參數、Secrets 與選用服務
* 具備健康檢查、自動重啟與日誌管理機制
