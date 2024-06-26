# CogVLM2


## 设置python虚拟环境

```bash
> sudo apt install python3-venv python3-pip
> mkdir /opt/Data/PythonVenv
> cd /opt/Data/PythonVenv
> python3 -m venv CogVLM2
> source /opt/Data/PythonVenv/CogVLM2/bin/activate
```

## 部署推理环境
```bash
> pip install -r requirements.txt -i https://pypi.tuna.tsinghua.edu.cn/simple
```

## notebook

```bash
> jupyter notebook --no-browser --port 7000 --ip=192.168.2.200
>
```

## 推理测试
```bash
> python basic_demo/cli_demo.py
> 
```