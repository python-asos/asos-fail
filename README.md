# asos-fail
ASOS executor plugin that fails occasionally

## Parameters

You can configure the executor by setting the following parameters in the task:

```json
"fail_period": N
```

## ASOS Task example

```json
{
  "task_type": "fail",
  "task_interval": 20,
  "fail_period": 5
}
```
