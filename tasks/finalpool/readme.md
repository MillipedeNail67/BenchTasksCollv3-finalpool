# tasks/finalpool

The final pool of **implemented** tasks collected from the latest task-adding commit of each
developer branch of `toolathlon/BenchTasksCollv3`.

A task counts as *implemented* when it satisfies the requirements documented in
`tasks/examples/example-task`:

* `docs/task.md` and `docs/agent_system_prompt.md` must be non-empty and written in English,
* the evaluation script `evaluation/main.py` must exist.

`docs/user_system_prompt.md`, `preprocess/main.py`, `initial_workspace/` and
`groundtruth_workspace/` are optional and were copied only when they exist in the developer branch.

## Tasks in this pool (latest commits, reviewed 2026-08-26)

| task | developer branch | task dir in the dev branch |
| --- | --- | --- |
| loyalty-program | fan-dev | tasks/fan/loyalty-program |
| discount-calculator | fan-dev | tasks/fan/discount-calculator |
| tag-manager | gyy | tasks/gyy/tag-manager |
| robots-handler | gyy | tasks/gyy/robots-handler |
| media-organizer | haoze | tasks/haoze/media-organizer |
| streaming-service | haoze | tasks/haoze/streaming-service |
| customer-feedback-processor | jl_dev | tasks/jl/customer-feedback-processor |
| inventory-management | jl_dev | tasks/jl/inventory-management |
| help-desk | junteng_dev | tasks/junteng/help-desk |
| social-connector | junxian_dev | tasks/junxian/social-connector |
| territory-manager | lueyang-dev | tasks/lueyang/territory-manager |
| client-portal | lueyang-dev | tasks/lueyang/client-portal |
| survey-builder | lv | tasks/lv/survey-builder |
| analytics-dashboard | lv | tasks/lv/analytics-dashboard |
| web-crawler | ruige | tasks/ruige/web-crawler |
| log-analyzer | ruige | tasks/ruige/log-analyzer |
| cache-optimizer | wenshuo-dev | tasks/wenshuo/cache-optimizer |
| scheduler | wenshuo-dev | tasks/wenshuo/scheduler |
| status-checker | xiaochen_dev | tasks/xiaochen/status-checker |
| health-monitor | xiaochen_dev | tasks/xiaochen/health-monitor |
| sync-service | yuxuan-dev | tasks/yuxuan/sync-service |
| certificate-manager | zhaochen | tasks/zhaochen/certificate-manager |
| storage-manager | zhaochen | tasks/zhaochen/storage-manager |

Excluded as *implementing* (they do not satisfy the requirements): sitemap-generator (gyy) and
customer-portal (junteng_dev) have no `evaluation/main.py`; currency-converter (junxian_dev),
insights-engine (lv), audit-logger (yuzhen-dev) and resource-monitor (yuzhen-dev) contain Chinese
(non-English) documentation.
