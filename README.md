# Hi, I'm kun wang 👋

**低温输运测量 · 实验室仪器自动化**

把台面上重复的手工操作，写成可复现、可追溯的程序。

---

## 在做的事

### 🔬 [Oxford Sequence Studio](https://github.com/w125342201-rgb/oxford-sequence-studio)

Oxford TeslatronPT 低温输运测量系统的序列化自动测量程序。

把「温度 × 磁场 × 角度 × 电极组」的组合扫描写成一份 JSON，由引擎逐点等到位、逐组换电极、逐次采集，同时输出 `data.csv` / `events.jsonl` / `run.json` 三份可以互相校验的数据。

支持两条测量链路：Keithley 2182A + 6221（Delta 三点法）、NI PXI-4462（交流激励 + 四通道同步数字锁相）。

`Python` · `Tkinter` · `PyVISA` · `NI-DAQmx` · `ISOBUS`

### 🎛️ 电动位移台上位机

位移台 + 相机的自动控制与采图。整理中。

---

## 关心的东西

- **实验数据要可复现** —— 配置和每一条事件都落盘，半年后还能说清那次测量到底怎么跑的
- **仪器控制要安全优先** —— 异常时关源、磁场 HOLD，而不是硬着头皮继续
- **写代码要承认边界** —— 哪些在实机上长期跑过、哪些只在单元测试里通过，分清楚写在 README 里

---

*有问题或建议，直接到对应仓库开 Issue。*
