# PowerEmbed

Requirement:
```
pip install requests ogb
pip install dgl-cu101 -f https://data.dgl.ai/wheels/repo.html
```

Run experiments for Reddit:
```
python sign.py --dataset reddit --random-walk --R 6
```

Run experiments for Amazon:
```
python sign.py --dataset amazon --random-walk --R 6
```
