# Grok Imagine 2.0 API 한국어 가이드（grok-imagine-2.0 / grokimagine2.0）

> 종량제, 최소 1달러 충전, OpenAI 호환 엔드포인트. **upload-image $0; default $0.015; region-edit $0.015**

**[模型页](https://go.apimart.ai/k-b3541d) · [实时价格](https://go.apimart.ai/k-4895c4) · [获取 API Key](https://go.apimart.ai/k-445378)**

## 가격（快照 2026-09-24）

| 档位 | 单价 |
| --- | --- |
| `upload-image` | $0 |
| `default` | $0.015 |
| `region-edit` | $0.015 |

按量计费、**$1 起充**，无订阅、无免费额度；每次任务响应返回 `cost` / `credits_cost`。

## 调用示例

```bash
curl --request POST --url https://api.apimart.ai/v1/images/generations \
  --header "Authorization: Bearer $APIMART_API_KEY" --header 'Content-Type: application/json' \
  --data '{"model":"grok-imagine-2.0-ext","prompt":"海边悬崖的现代别墅，黄昏","size":"16:9","n":1}'
```

## 披露

이 저장소는 서드파티 중계 서비스 APIMart 사용 가이드입니다.
