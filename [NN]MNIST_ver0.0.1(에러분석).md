# 에러분석

```python
train_dataloader   =   DataLoader(dataset=train_dataset, batch_size=batch_size)
test_dataloader    =   DataLoader(dataset=train_dataset, batch_size=batch_size)
```

부분 CUDA에러 문제

: 해당 에러는 MNIST 데이터셋에서 shuffle과 num_workers 가 추가될경우 발생함