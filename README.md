# ips2range

## 方便攻防场景中快速聚合目标所拥有的c段或者b段
## usage
```
首先进入当前目录将源代码编译
cargo build --release

```
``` 
./ips2range c ips.txt 
第一个参数指定要筛选c段还是b段，第二个参数指定文件，每行一个ip    
```
### 参数c筛选C段，如果要筛选B段就把参数c换成参数b

<img width="634" alt="image" src="https://user-images.githubusercontent.com/38530231/154810419-51b27216-0f9f-4027-b43d-cc9da08eca5c.png">
<img width="556" alt="image" src="https://user-images.githubusercontent.com/38530231/154810459-58484542-afc3-42ae-bbe1-e4991427d662.png">

