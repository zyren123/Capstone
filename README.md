
# Llava_Eval

生成结果的评估代码,将模型输出结果格式整理为prediction_answer.json中的格式，将所有可能的选项整理为candidate.json


## 在本地运行

Clone 这个 project

```bash
  git clone https://github.com/zyren123/Capstone.git
```

前往项目目录

```bash
  cd Capstone
```

安装依赖

```bash
  pip install -r requirements.txt 
```

启动评估

```bash
python run_eval.py --gt prediction_answer.json ^
    --pred prediction_answer.json ^
    --candidate candidate.json
```

