# Lab 1 Submission

## 1. Repo 連結
https://github.com/你的帳號/wsse-student-enrollment-labs-2025

## 2. PR 連結
https://github.com/你的帳號/wsse-student-enrollment-labs-2025/pull/1

## 3. Swagger Editor 截圖
- 01-editor.png  
（右側無紅字，並標註 Raw URL）

## 4. PR 綠燈截圖
- 02-pr-green.png  
（顯示 OpenAPI Minimal CI 通過）

## 5. CI 驗證成功截圖
- 03-actions-log.png  
（swagger-cli validate 成功）

## 6. 重點片段連結
- `/health`  
  https://github.com/你的帳號/wsse-student-enrollment-labs-2025/blob/main/openapi/openapi.yaml#L52-L74
- `GET /students`  
- `POST /students (201 + Location)`  
- `Student / Error Schema`

## 7.（若已完成）ApiKey 與 /health 覆寫
- components.securitySchemes.ApiKeyAuth
- /health security: []
